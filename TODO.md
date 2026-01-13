# TODO List - One-to-One and One-to-Many Relationships

## Phase 1: Update models.py
- [x] Add `employee_id` FK and `employee` relationship to Review model
- [x] Add `reviews` relationship with cascade to Employee model
- [x] Add `employee_id` FK and `employee` relationship to Onboarding model
- [x] Add `onboarding` relationship with `uselist=False` to Employee model

## Phase 2: Update seed.py
- [x] Add relationship assignments for Reviews (use employee= instead of employee_id=)
- [x] Add relationship assignments for Onboarding (use employee= instead of employee_id=)

## Phase 3: Database Setup
- [ ] Run `flask db migrate -m "add relationships"`
- [ ] Run `flask db upgrade head`
- [ ] Run `python seed.py` to seed the database

## Phase 4: Verify
- [ ] Run tests to verify implementation

