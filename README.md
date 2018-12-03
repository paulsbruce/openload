# openload
An open descriptor format for performance testing and analysis models.

The goal of the OpenLoad spec is to define key characteristics of a performance validation plan against one or more distributed systems, including:

 - how to put pressure on a system under test (i.e. load testing)
    - scalable test design (simulation definition)
    - execution and distribution plans (simulation infrastructure)
 - what telemetry is required to determine impact of pressure
    - key performance indicators (expectations; SLA, SLI, SLO)
 - how to interpret system impact in terms of business value
    - analysis and mathematical aggregation models
    - references to external processes and KPIs

# performance and load testing

Performance testing refers to the capability to verify that actual performance characteristics of a system meet stated requirements. This means that the system behavior must be observable and that performance characteristics must be reproducible.

Load testing refers to the practice of putting pressure on a system. This pressure can be made to be very realistic or can be scoped to a particular area for fault isolation purposes. Various models of pressure include:

 - fixed load (a constant volume of pressure)
 - ramped load (an increasing and/or decreasing volume of pressure)
 - oscillating load (switching between two volumes at intervals)
 - arbitrary load (along a time-based distribution curve)
