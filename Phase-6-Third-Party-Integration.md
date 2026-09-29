# Phase 6: Third-Party API & Platform Integration

### Mock API Integration (as per PDF):
- Amazon, Flipkart - for Home & Jewelry products
- IKEA - for Home decor
- Swiggy, Zomato - for Party catering
- OYO - for Venue/Accommodation

### Implementation:
- get_home_recommendations() -> linking websites to get products
- get_party_recommendations() -> categorize by event type
- get_jewelry_recommendations() -> style matching

### Logic:
- if budget < 5000: suggest budget products
- if outfit_image provided: analyze color via Gemini Vision
- Return JSON: {product_name, price, platform, link, reason}
