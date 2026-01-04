# TODO: Flask-SQLAlchemy One-to-Many and One-to-One Relationships

## Phase 1: Update server/models.py

- [x] Add employee_id ForeignKey column to Review model
- [x] Add employee relationship to Review model with back_populates
- [x] Add employee_id ForeignKey column to Onboarding model
- [x] Add employee relationship to Onboarding model with back_populates
- [x] Add reviews relationship to Employee model with back_populates and cascade
- [x] Add onboarding relationship to Employee model with uselist=False, back_populates and cascade

## Phase 2: Update server/seed.py

- [x] Update Review creation to use object references
- [x] Update Onboarding creation to use object references

## Phase 3: Database Operations

- [ ] Run flask db migrate to create migration
- [ ] Run flask db upgrade head to apply migration
- [ ] Run python seed.py to seed the database

## Phase 4: Testing

- [ ] Verify relationships work in Flask shell
