## Week 5: WCAG 2.2 AA

| Screen | Element | Foreground | Background | Contrast Ratio | WCAG 2.2 AA Requirement | Result |
|--------|---------|------------|------------|----------------|-------------------------|--------|
| Checkout | Page Title | `#000000` | `#FFFFFF` | 21:1 | ≥ 4.5:1 | ✅ Pass |
| Checkout | Product Name | `#295174` | `#DFF1F2` | 7.13:1 | ≥ 4.5:1 | ✅ Pass |
| Checkout | Body Text | `#0E1E45` | `#FFFFFF` | 16.27:1 | ≥ 4.5:1 | ✅ Pass |
| Checkout | Primary Button Text | `#FFFFFF` | `#295174` | 8.32:1 | ≥ 4.5:1 | ✅ Pass |
| Checkout | Secondary Button Text | `#56617D` | `#FFFFFF` | 6.17:1 | ≥ 4.5:1 | ✅ Pass |
| Checkout | Input Border | `#244664` | `#FFFFFF` | 9.83:1 | ≥ 4.5:1 | ✅ Pass |
| Checkout | Error Text | `#DC2626` | `#FFFFFF` | 4.83:1 | ≥ 4.5:1 | ✅ Pass |
| Checkout | Success Text | `#2D6A4C` | `#FFFFFF` | 6.4:1 | ≥ 4.5:1 | ✅ Pass |
| Checkout | Progress Stepper | `#295174` | `#DFF1F2` | 7.13:1 | ≥ 4.5:1 | ✅ Pass |
| Checkout | Disabled Text | `#464554` | `#FFFFFF` | 9.37:1 | ≥ 4.5:1 | ✅ Pass |
| Checkout | Out of stock label | `#F1BF41` | `#FCEEED` | 1.51:1 | Exempt (non-interactive) | Review |
| Checkout | Out of stock label | `#9D5E0B` | `#FCEEED` | 4.6:1 | ≥ 4.5:1 | ✅ Pass |
| Coupon | Coupon code | `#0E1E45` | `#E5F4F5` | 14.4:1 | ≥ 4.5:1 | ✅ Pass |
| Coupon | Icon | `#0E1E45` | `#B6E1E2` | 11.51:1 | ≥ 4.5:1 | ✅ Pass |
| Coupon | Secure Check | `#1B1B23` | `#FEFAFA` | 16.51:1 | ≥ 4.5:1 | ✅ Pass |
| Coupon | Order successful text | `#295174` | `#F0FEFF` | 8.05:1 | ≥ 4.5:1 | ✅ Pass |
| Invalid Payment | Card of payment opt. | `#EB483E` | `#F9FDFD` | 3.7:1 | Exempt (non-interactive) | Review |
| Payment Declined | Card tab error | `#1B1B23` | `#FCEFEF` | 16.51:1 | ≥ 4.5:1 | ✅ Pass |

## Week 5: INTENDED Tab order of Invalid Payment

| Order | Element |
|------:|---------|
| ① | Back Button |
| ② | Progress Stepper |
| ③ | Recommend for You – Payment Method: Cash on Delivery (COD) |
| ④ | Payment Method – UPI |
| ⑤ | Credit/Debit Card / ATM Card |
| ⑥ | Card Number Field |
| ⑦ | Expiry Date Field |
| ⑧ | CVV Field |
| ⑨ | Pay Later |
| ⑩ | EMI |
| ⑪ | Net Banking |
| ⑫ | Cash on Delivery (Cash/UPI) |
| ⑬ | Have a Gift Card? |
| ⑭ | Terms & Conditions Checkbox |
| ⑮ | Pay Now Button |

## Week 5: INTENDED Tab order of Declined Payment

| Order | Element |
|------:|---------|
| ① | Back Button |
| ② | Terms & Conditions Checkbox |
| ③ | Contact Support |
| ④ | Try Another Payment Method – Navigates the user to alternative payment options such as UPI, Card, Wallet, or Cash on Delivery |
| ⑤ | Retry Transaction |