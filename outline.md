# Cato Neimoidia Shipping Design Documentation
## Purpose
Manage ships and crews on the Quellor Run

## Database
- Ships
  - shipID
  - shipName
  - capacity
  - range
  - statusID
- Personelle
  - id
  - name
  - rank
  - jobTitle
  - status
- Routes
 - routeId
 - planets
 - cargoType
- cargo
  - id
  - type
  - destination
  - status


# App Stucture
- Main - overview
- Ships
- personelle
- routes
- cargo

# Functionality
- CRUD on ships
- CRUD on Personelle
- CRUD on Routes
- CRUD on cargo
- assign crew to ships
- assign ships to routes
- assign cargo to ships
- overview
