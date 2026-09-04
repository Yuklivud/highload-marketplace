Product 
- id
- name
- description
- categoryId
- brand
- status // DRAFT, ACTIVE, ARCHIVED
- version
- createdAt
- updatedAt

UserProfile
- id
- displayName
- status
- createdAt
- updatedAt

SellerProfile
- id
- userId
- shopName
- description
- status // PENDING, ACTIVE, SUSPENDED
- createdAt
- updatedAt

Offer
- id
- productVariantId
- sellerId
- price
- currency                  // EUR, USD, etc.
- status
- version
- createdAt
- updatedAt

Order
- id
- customerId
- status
- currency
- subtotal
- deliveryPrice
- total
- shippingAddressSnapshot
- createdAt
- updatedAt

OrderItem
- id
- orderId
- offerId
- productId
- sellerId
- productNameSnapshot
- skuSnapshot
- unitPrice
- quantity
- totalPrice

Review
- id
- productId
- customerId
- orderItemId
- rating // 1–5
- comment
- status
- createdAt
- updatedAt

RatingSummary
- productId
- averageRating
- reviewCount


