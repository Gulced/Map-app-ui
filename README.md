# MapApp Angular Client

The separately stored Angular/OpenLayers web client for the MapApp project family.

## Overview

The separately stored Angular/OpenLayers web client for the MapApp project family. The description and capabilities in this document are limited to behavior that can be verified in the repository source.

## Key Features

- Authentication UI
- Administrative views
- Interactive map module
- API service layer

## Tech Stack

- TypeScript
- Angular
- OpenLayers
- RxJS

## Architecture

Angular feature areas separate authentication, administration, map, menu, and service responsibilities.

## Project Structure

- `src/app/auth/` — authentication UI
- `src/app/admin/` — administrative views
- `src/app/map/` — OpenLayers map feature
- `src/app/services/` — API clients

## Getting Started

Run the commands appropriate to the project root:

```bash
npm install
npm start
```

## Testing

```bash
npm test
```

## Technical Highlights

- OpenLayers map interface
- Angular feature organization
- Backend service integration

## Possible Improvements

- Add or expand automated tests around core workflows.
- Document deployment and environment-specific configuration.
- Add CI checks for build, linting, and tests where they are not already present.

## Verification Notes

This is a frontend component of the broader MapApp project family and should be grouped with MapApp on a CV.
