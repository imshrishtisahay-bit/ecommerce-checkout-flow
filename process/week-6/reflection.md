# week:6 Reflection

## Steps I Got Stuck During the Task

### 1. Keyboard Navigation & Accessibility

**Constraint:**  
Figma does not support true keyboard navigation using the **Tab** key, automatic focus traversal, or keyboard-only interaction within prototypes.

**Workaround:**  
Documented the intended keyboard focus order and accessibility behavior through annotations. These interactions are intended for implementation during frontend development (HTML/CSS/JavaScript) following **WCAG 2.2 AA** guidelines.

---

### 2. Input Field & Micro-interactions

**Constraint:**  
Figma cannot simulate live text entry, a blinking text cursor (caret), automatic focus movement between input fields, or real-time form validation.

**Workaround:**  
Used interactive component variants, Smart Animate, and predefined states (**Default, Hover, Focus, Filled, Error, Disabled**) to demonstrate the intended user experience.

---

### 3. Dynamic User Flows

**Constraint:**  
Figma cannot use a single interaction to generate different outcomes based on user input. For example, the **Pay Now** button cannot automatically navigate to either **Order Success** or **Payment Failed**, and coupon validation cannot dynamically determine valid or invalid results.

**Workaround:**  
Created separate prototype flows to represent the Happy Path and each edge-case scenario.

---

### 4. Multiple Branching Scenarios

**Constraint:**  
The checkout journey included multiple branching paths:

- Happy Path
- Coupon Applied
- Coupon Expired / Invalid
- Shipping Validation Error
- Payment Failure & Retry

Displaying all possible outcomes within one continuous prototype is not feasible in Figma.

**Workaround:**  
The prototype was divided into four independent flows:

- Happy Path Checkout
- Coupon Edge Cases
- Payment Failure
- Shipping Validation

This ensured each scenario could be demonstrated clearly and independently.

---

### 5. Prototype Sharing & Submission

**Constraint:**  
Figma shares the entire design page instead of only selected prototype flows. Additionally, the submission portal did not support uploading a `.txt` file containing the prototype URL.

**Workaround:**  
Created a PDF containing a **view-only hyperlink** to the Figma prototype, allowing reviewers to access the interactive prototype while meeting the submission requirements.

---

### 6. Prototype Interaction Limitation

**Constraint:**  
Figma does not allow text fields to accept real keyboard input or navigate directly to another screen. Interactive elements such as buttons or hotspots must be used to trigger navigation.

**Workaround:**  
Text fields were treated as visual components, while navigation was handled using dedicated buttons and interactive hotspots to simulate the intended checkout experience.

---

## Conclusion

Although Figma has limitations in simulating real application behavior, keyboard accessibility, conditional logic, and branching interactions, these constraints were addressed through interactive components, multiple prototype flows, accessibility annotations, and a dedicated prototype link. This approach enabled a realistic demonstration of both the primary checkout journey and key edge-case scenarios while remaining within Figma's prototyping capabilities.