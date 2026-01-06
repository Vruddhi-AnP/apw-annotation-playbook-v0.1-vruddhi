Label Specification & Edge Cases – Support-Routing-60

Categories
- refund_request: refund, cancellation, return requests
- order_status: delivery delay, tracking, order status queries
- product_issue: damaged, wrong, defective product
- account_access: login issues, OTP not received, email update
- spam_other: promotional, scam, irrelevant messages

Entity Rules
- order_id: strings like ORD12345
- phone: valid phone numbers with or without country code
- email: valid email patterns

Edge Cases
1. Mixed spam + support request → spam_other
2. OTP + login issues → account_access
3. Promo text + real issue → classify by dominant intent

Assumptions
- Single category per message
- Entities captured only when explicitly present
