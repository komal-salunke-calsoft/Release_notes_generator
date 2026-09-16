
## Release Summary...

This major release changes profile lookup validation and requires a valid
user ID for every profile request.

## Breaking Changes

- Profile lookup now requires a valid user ID.
- Existing clients that call profile lookup without a user ID must be updated.

## Migration Instructions

Update existing clients to provide a valid user ID when requesting a profile.

## Technical Details

- Added mandatory user ID validation.
- Updated API documentation.
- Added a breaking-change marker to the commit.
