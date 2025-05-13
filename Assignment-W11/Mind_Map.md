```mermaid
mindmap
  root((Hotel Booking Cancellation))
    Introduction
      Technology eases access to information
      Online hotel reservations
      Ease of cancellation leads to uncertainty
      Financial loss from sudden cancellations
    Problem Statement
      Predict cancellation using ML models
      Measure model performance
      Identify cancellation factors
    Objectives
      Minimize false negatives
      Identify loss causes
      Provide policy insight for hotels
    Production Scenario
      Dynamic factors influencing cancellation
      Monthly analysis and review
      Evaluate effectiveness of improvements
    Metric Evaluation
      Use Recall as main metric
        Recall = TP / (TP + FN)
      Minimize False Negatives
        FN: predicted not canceled, actually canceled
        Impact: revenue loss, inefficiency
