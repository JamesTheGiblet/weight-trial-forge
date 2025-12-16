⚖️ TrialForge - Metabolic Retention Analytics

TrialForge: Metabolic is a specialized predictive analytics tool for Chronic Weight Management and Obesity clinical trials.

It specifically addresses the "Plateau Effect"—the critical window (usually Month 3-6) where weight loss slows, motivation plummets, and dropout rates spike. This tool helps study teams model how digital interventions can sustain engagement during this vulnerability phase.
✨ Key Features

    Plateau Modeling: The risk algorithm is heavily weighted towards "Biological Factors" (Weight Trend), reflecting the reality that clinical outcomes drive behavior in obesity trials.

    Metabolic-Specific Inputs: Tracks inputs relevant to GLP-1/GIP trials, such as Injection Compliance, Smart Scale Syncing, and Caloric Logging Burden.

    Interaction Maintenance: Simulates the impact of "High-Touch" interventions (e.g., Virtual Dietitians, Peer Support) vs. "Low-Touch" tech (e.g., Apps).

    Just-in-Time Alerts: Demonstrates how predictive models can trigger automated support protocols exactly when a patient hits a weight loss plateau.

🚀 Quick Start

    Launch: Open index.html in a web browser.

    Simulate a Patient:

        Set "Weight Trend" to Plateau (No change).

        Set "Adverse Events" to Mild/Transient (common with GLP-1s).

    Deploy Interventions: Activate Smart Scale + Auto-Sync and Virtual Dietitian Consult.

    Observe: Watch how the "Dropout Timeline" shifts from "4-6 Weeks" to "Stable."

🧮 The Logic: Motivation Decay

This tool adapts the standard Forge Theory decay model to behavioral psychology in weight loss.
Motivationt​=(WeightLossVelocity×0.4)+(Engagement×0.6)×e−k⋅t

    k (Decay Rate): In weight management, k accelerates when WeightLossVelocity approaches zero (The Plateau).

    Interventions: Tools like Smart Scales reduce the friction of logging, effectively lowering k by removing administrative burden.

⚙️ Configuration

The risk weights are defined in the EXAMPLE_FACTORS object. You can adjust these to model different obesity phenotypes or trial phases.
JavaScript
