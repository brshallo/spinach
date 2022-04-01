# spinach
**S**imulating **P**rediction **IN**tervals **A**nd **CH**ance -- placeholder for a tidymodels friendly package for a generalizable approach to simulating uncertainty in predictions. See {spin} for initial toy package that contains some initial notes on API: https://github.com/brshallo/spin

- end-goal would be to pass in a tidymodels workflow (that may include e.g. a parsnip model specification, a preprocessing recipe, a cross-validation resampling scheme) and would output an object that could be used in a `predict()` method to provide uncertainty levels for new observations.
- see field of conformal inference for broad range of approaches / "uncertainty specifications" that may look to set-up.
