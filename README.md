## Use Case Diagram

```mermaid
useCaseDiagram
    actor User as "User / Admin"
    
    package "SLA Breach Prediction System" {
        (Upload & Validate Dataset)
        (View Data Preview & Info)
        (Explore Data Visualizations)
        (Predict SLA Breach Risk)
        (View Performance Dashboard)
        (View System Design & Requirements)
    }
    
    User --> (Upload & Validate Dataset)
    User --> (View Data Preview & Info)
    User --> (Explore Data Visualizations)
    User --> (Predict SLA Breach Risk)
    User --> (View Performance Dashboard)
    User --> (View System Design & Requirements)
    
    note left of (Upload & Validate Dataset)
      Includes:
      • Validate CSV Schema
      • Auto-compute Columns
      end note
    
    note right of (Predict SLA Breach Risk)
      Includes:
      • Load Trained Model
      • Return Risk Level
      end note
