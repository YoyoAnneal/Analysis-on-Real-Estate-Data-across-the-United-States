# Predictive Modeling and Analysis

  ## Classification 1: Owned vs Leased
    Objective: Predict whether a building is government-owned or leased
    Models Used: Logistic Regression, KNN, Decision Tree, Random Forest
    Insight: Building age, property type, and parking capacity strongly influence ownership decisions
  ## Classification 2: Historical Status
    Objective: Identify whether a building has historical significance
    Model Used: Random Forest Classifier
    Insight: Older buildings and certain property types are more likely to be historically designated
  ## Classification 3: ABA Accessibility Compliance
    Objective: Predict compliance with Architectural Barriers Act standards
    Model Used: Random Forest Classifier
    Insight: Building age, ANSI usable area, city, and parking availability are key drivers of accessibility compliance
  ## Classification 4: Has Parking
    Objective: Determine whether a building provides parking facilities
    Models Used: Logistic Regression and Tree-based classifiers
    Insight: Larger buildings and newer constructions are more likely to include parking infrastructure
  ## Regression 1: Building Age
    Objective: Predict building age based on structural and location features
    Models Used: Linear, Ridge, Lasso, Decision Tree
    Insight: Year built is the dominant predictor, with regularized models improving stability
  ## Regression 2: Total Parking Spaces
    Objective: Estimate parking capacity
    Model Used: Gradient Boosting Regressor (with log transformation)
    Insight: Moderate predictive performance due to high skewness and external zoning factors
  ## Regression 3: Year Built
    Objective: Predict construction year
    Model Used: Random Forest Regressor
    Insight: Structural attributes and usable area strongly influence predictions
  ## Regression 4: Building ANSI Usable Area
    Objective: Predict usable building area
    Model Performance: R² ≈ 0.476
    Insight: Structural features explain nearly half the variability, but architectural details are missing
