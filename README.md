# Markus Stitka

Software engineer and technical co-founder of [itemary](https://itemary.de).

Currently working across TypeScript, Go, mobile, backend and cloud systems.
I am particularly interested in reliable backend software and products
that solve real-world problems.

Most of my recent production work is maintained in private repositories.

## Selected project

[Wattfeder](https://github.com/Stewz00/Wattfeder) 

A Go edge agent for a household energy system. It reads solar production, load, battery charge and electricity price, and decides every interval whether to charge, discharge or idle the battery.

Telemetry in the real world arrives twice, arrives late, arrives broken, or does not arrive at all. Wattfeder gives every observation one explicit outcome, and one bad observation never stops the ones after it. State is stored transactionally in SQLite and survives restart. The running agent exposes health endpoints, Prometheus metrics and OpenTelemetry traces.

Two commands run the whole thing: `make demo` and `make demo-faults`.

[LinkedIn](https://www.linkedin.com/in/markus-stitka-530892237/)
