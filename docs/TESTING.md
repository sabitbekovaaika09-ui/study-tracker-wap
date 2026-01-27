# Testing

## Manual Testing Checklist

### Authentication
- Register with new email → success
- Login with correct password → success
- Login with wrong password → error

### Authorization
- Open protected pages without token → blocked
- Access tasks of another user → not allowed

### Tasks CRUD
- Create task → appears in list
- Edit task → updated correctly
- Change status → updates correctly
- Delete task → removed

### Deadlines
- Create task with past deadline → marked as overdue
- Mark overdue task as Done → overdue label disappears

## Future Automated Tests (optional)
- Unit tests for controllers/services
- Integration tests for API endpoints
