## 📊 Use Case Diagram

```mermaid
usecaseDiagram
    actor User
    
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
