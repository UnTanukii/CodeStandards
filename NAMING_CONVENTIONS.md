# Naming Conventions

A concise guide to different naming conventions and their uses in programming.

---

## Why Naming Conventions Matter
- **Readability:** Improves code clarity for teams.
- **Consistency:** Creates a uniform coding style.
- **Maintainability:** Simplifies long-term code updates.

---

## Naming Convention Types

### 1. **camelCase**
- **Definition:** Words are joined without spaces, starting with a lowercase letter. Each subsequent word starts with an uppercase letter.
- **Usage:** Variables, functions.
- **Example:**
```javascript
let userName = "John";
function getUserData() {
  // logic here
}
```

### 2. **PascalCase**
- **Definition:** Similar to camelCase but starts with an uppercase letter.
- **Usage:** Class and type names.
- **Example:**
```javascript
class UserProfile {
  constructor(name) {
    this.name = name;
  }
}

let ProductManager = new UserProfile("Alice");
```

### 3. **snake_case**
- **Definition:** Words are separated by underscores and written in lowercase.
- **Usage:** Variables, file names in some languages (e.g., Python).
- **Example:**
```python
user_name = "John"
def get_user_data():
    # logic here
    pass
```

### 4. **kebab-case**
- **Definition:** Words are separated by hyphens and written in lowercase.
- **Usage:** CSS class names, file names in some contexts.
- **Example:**
```css
.user-name {
  font-size: 16px;
}

.button-primary {
  background-color: blue;
}
```

### 5. **MACRO_CASE**
- **Definition:** Words are separated by underscores and written in uppercase.
- **Usage:** Constants, preprocessor directives.
- **Example:**
```c
#define MAX_LIMIT 100
const char* CONFIG_PATH = "/etc/config";
```

### 6. **Train-Case**
- **Definition:** Similar to PascalCase but with hyphens separating words.
- **Usage:** Titles, certain specific use cases.
- **Example:**
```text
User-Profile
Invoice-Number
```

---

## Best Practices
- **Consistency:** Use the same convention for similar entities.
- **Contextual Usage:** Match conventions to their common purposes.
- **Documentation:** Document naming rules in the project guidelines.

---

## Example Workflow
1. Choose a convention based on the entity:
   - Variables: `camelCase` or `snake_case`.
   - Classes: `PascalCase`.
   - Constants: `MACRO_CASE`.
2. Apply consistently across the codebase.
3. Review during code reviews to ensure adherence.

---

Follow these conventions to improve code readability and maintainability!

