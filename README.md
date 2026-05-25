# Drone Robotics Inspection Suite

Wave:
- Portfolio next-20 completion batch

Source candidates represented:
- `AIDroneRoboticsInspectionAssistant`
- `AIDroneRoboticsInspectionOperations`
- `AIDroneRoboticsInspectionAnalytics`
- `AIDroneRoboticsInspectionWorkflow`

This suite is a runnable merged app with one login, one dashboard, one feature-first sidebar, PostgreSQL-backed records/documents/notifications/audit, role behavior, and smoke coverage.

## Local Run

```bash
cd /Users/erolakarsu/projects/merged/drone-robotics-inspection-suite
./start.sh
```

Local URL:
- `http://127.0.0.1:4810`

Seeded users:
- `admin@drone-robotics-inspection.local / admin123`
- `manager@drone-robotics-inspection.local / manager123`
- `analyst@drone-robotics-inspection.local / analyst123`

## Validation

```bash
cd /Users/erolakarsu/projects/merged/drone-robotics-inspection-suite/frontend
npm run typecheck
SMOKE_BASE_URL=http://127.0.0.1:4810 npm run smoke
```
