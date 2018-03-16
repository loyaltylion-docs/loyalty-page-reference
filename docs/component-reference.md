# LoyaltyLion UI component reference

## Simple components

### Customer points

You can render the customer's current points using the following elements:

```html
<!-- customer's total (approved + pending) points -->
<span data-lion-points></span>

<!-- customer's approved (redeemable) points -->
<span data-lion-points='approved'></span>

<!-- customer's pending points -->
<span data-lion-points='pending'></span>

<!-- customer's spent points -->
<span data-lion-points='spent'></span>

<!-- customer's lifetime (approved + pending + spent) points -->
<span data-lion-points='lifetime'></span>
```

### Signup points

You can render the number of points given for signups with the following element:

```html
<span data-lion-points-for='signup'></div>
```

## Complex components

### Rules list

This component will render a list of rules. If a shopper is logged in, the rules will be actionable and, when clicked on, will open a modal with additional information or actions (e.g. enter birthday)

Code:

```html
<div data-lion-rules-list></div>
```

Example:

![rules list](https://d.pr/i/weRgL7.png)

### Rewards list

This component will render a list of rewards. If a shopper is logged in, the rewards will have a "Redeem" button that can be clicked to open the claim reward modal.

Code:

```html
<div data-lion-rewards-list></div>
```

Example:

![rewards list](https://d.pr/i/pX2Yom.png)

### Claimed rewards list

This component will render a list of claimed rewards for the currently logged in customer.

Code:

```html
<div data-lion-claimed-rewards-list></div>
```

Example:

![claimed rewards](https://d.pr/i/I0QHnj.png)

### History table

This component will render a table containing the currently logged in customer's history (points earned and redeemed).

Code:

```html
<div data-lion-activity-history></div>
```

Example:

![history table](https://d.pr/i/tIYNy1.png)

## Modals

Many actions in LoyaltyLion will trigger a modal. The modal we render will always share the same base styles, but some modals will have additional functionality.

### Rule modal

![rule modal](https://d.pr/i/GBmEy5.png)

### Redeem reward modal

![redeem modal](https://d.pr/i/VwmYlz.png)

### Claimed reward modal

![claimed reward modal](https://d.pr/i/zGOJow.png)

### History info modal

![history info modal](https://d.pr/i/TOP2ie.png)
