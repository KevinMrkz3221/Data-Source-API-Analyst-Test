# Troubleshooting Guide

## Error: 401 Unauthorized
- Check that the token is active
- Use the header `Authorization: Bearer YOUR_TOKEN`
- Make sure you have sufficient permissions

## Error: Rate Limit Exceeded
- GitHub limits requests per hour:
  - 60 without token
  - 5000 with token
- Solution: wait 1 hour or use authentication

## Error: 404 Not Found
- Check the owner and repository name
- Check that the path in `contents/{path}` exists