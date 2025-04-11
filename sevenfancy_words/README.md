### a. Idempotent
- **Latin origin**: *idem* (the same).  
- Code produces the same result when run multiple times.  
- Example:  
  - Adding an element to an array keeps pushing and changes the array, so the result is **not idempotent**.  
  - Using a `Set` and pushing the same variable ensures the set only contains unique elements, making it **idempotent**.  
- **Common use cases**: API calls and transactions.

---

### b. Ephemeral
- **Definition**: Lasting temporarily.  
- **In programming**: Opposite of persistent or immutable.  
- Example:  
  - RAM is ephemeral, while a hard disk is persistent.  
  - Cloud computing often uses ephemeral servers (e.g., AWS Lambda, Google Cloud Functions) that exist only when needed.  
  - **Ephemeral IP**: When a server shuts down, its IP address is reassigned.

---

### c. Anonymous
- **Definition**: Functions without a name.  
- **In programming**: Functions defined as arguments.  
- Examples:  
  - **JavaScript**: Arrow functions.  
  - **Python**: Lambda functions.

---

### d. Predicate
- **Definition**: A function that returns `true` or `false`.  
- **Use case**: Often used in type guards or to check conditions.

---

### e. Memoization
- **Definition**: "Mindful remembering."  
- **In programming**: Caching the return value of a function to avoid redundant calculations.

---

### f. Abstraction
- **Definition**: The process of hiding implementation details from the end user.  
- **Example**:  
  - **DRY principle**: "Do not repeat yourself" in coding.  
  - Abstract classes allow you to define methods that must be implemented in derived classes.

---

### g. Serialization
- **Definition**: Converting data from a native language format into a more generic format (e.g., JSON, XML) so it can be used by other programs or systems.

---