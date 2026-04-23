# Logging Design

## What is logged?

- API requests
- Response time
- Errors
- User actions

## Log format example:

{
  "timestamp": "2026-04-23",
  "service": "recommendation-api",
  "level": "INFO",
  "message": "User requested recommendations",
  "user_id": 1,
  "response_time_ms": 120
}

## Purpose:
- Debugging
- Performance tracking
- Error analysis
