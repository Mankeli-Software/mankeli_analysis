## 1.1.0
### Removes some bad linting rules
- **`arguments-ordering`**: 
    This rule was conflicting with `sort_child_properties_last` when using `flutter_bloc`. It was trying to force `builder` to be defined before `build_when`, which is NOT OK.
- **`avoid-banned-imports`**:
    This was an experimental rule, which often times lead to very project specific config. That is not something we want in our general linting rules, it should be defined within the project itself.

### Adds usage tutorial

## 1.0.0
### Initial release