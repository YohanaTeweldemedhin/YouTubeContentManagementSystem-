

# 📝 Commit Messages

## 🔹 Why They Matter

* Help track **what changed** and **why**.
* Make debugging, reviewing, and collaborating easier.
* Serve as a **project history log**.

---

## 🔹 Best Practices

1. **Use imperative mood** → “Add feature” not “Added feature”.
2. **Keep subject line short** (≤ 50 chars).
3. **Capitalize** first word.
4. **Don’t end with a period.**
5. If needed, add a detailed **body** (wrap at 72 chars).

---

## 🔹 Commit Message Format (Conventional Commits style)

```
<type>(<scope>): <short description>

[optional body]
[optional footer]
```

### Common Types:

* `feat`: new feature
* `fix`: bug fix
* `docs`: documentation changes
* `style`: formatting (no code change)
* `refactor`: restructuring code
* `test`: adding/fixing tests
* `chore`: maintenance tasks

---

## 🔹 Examples

✅ Good:

```
feat(auth): add JWT authentication
```

```
fix(data-cleaning): handle null values in age column
```

```
docs(readme): update setup instructions
```

❌ Bad:

```
update stuff
```

```
bug fixes
```

---
