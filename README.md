# SSH Brute-Force Detection Lab (Blue Team Practice)

## Objective
Simulate and detect SSH brute-force authentication attempts using system logs.

## Scenario
- Created a test user
- Performed 17 failed SSH login attempts
- Successfully authenticated once
- Investigated authentication logs using journalctl

```Commands Used
journalctl -u ssh -b
grep "Failed password"
grep "Accepted password"
```

## Analysis
- Identified rapid sequential failed login attempts
- Observed fail-to-success authentication pattern
- Practiced basic Blue Team log investigation

## Skills Practiced
- SSH authentication log analysis
- Pattern recognition
- Basic brute-force detection
- Linux journalctl usage
