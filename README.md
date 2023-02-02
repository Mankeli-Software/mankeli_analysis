# mankeli_analysis

A set of linting rules used internally at Mankeli Software for static analysis.

## Usage
1. Add `mankeli_analysis` and `dart_code_metrics` as dev dependencies in pubspec.yaml

```yaml
dev_dependencies:
  dart_code_metrics: any
  mankeli_analysis: any
```

2. Run `flutter pub get`

3. If not already created, create a `analysis_options.yaml` file in the root of the project

4. Add the following line to `analysis_options.yaml`
```yaml
include: package:mankeli_analysis/analysis_options.yaml
```

5. Enjoy your new clean code!