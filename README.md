# Pharmacy Inventory Management System Proposal
This is an system built for chains of pharmacy system to manage their inventory which imports from distributors and supplies for their sale stores.
This system written mainly in .NET and deploy automatically using Docker/GithubAction
Web admin client written in React and utilized React's ecosystem (Tanstack Query, Tanstack Table, Mantis).


Other versions in Java Spring/NestJs can be found at:

## I. Technical stack

- Monolith MVC main service in .NET 8
- Infrastructure
  - Postgres, Redis
  - Third party: Firebase, S3
  - docker and docker-compose
  - staging container for reproducible development environment
## II. Proposal system flows
### 1. Import flow 

![import_flow](docs/import-flow.svg)
### 2. Export flow
![export_flow](docs/export-flow.svg)
### 3. Check goods flow
![check-good](docs/check-good.svg)
## Demonstration
### Video

### Screenshots


## Development

### Overral Architecture
### Concept ERD
### Sequence Diagram


[Development project trouble shooting](https://github.com/thangchung/go-coffeeshop/wiki#trouble-shooting)

# Team members
- Trinh Khanh Linh (Lead)
- Le Thanh Phong
- Bui Dang Khoa
- Nguyen Manh Hung
- Nguyen Gia Tin
# Roadmap

- ✅ Add import flow (Basic - Assumption : enough resource/stock for exporting)
- ✅ Add export flow  (Basic)
- ✅ Add manage product flow
- 🕛 Dashboard
- Add Export flow (Partialy)
## Disclaimer

