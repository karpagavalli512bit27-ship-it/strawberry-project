# TODO — IEEE Paper Enhancements

## Backend (SE-ResNet for IEEE Paper)
- [x] Update `backend/model.py` with proper ResNet18/34 + SE blocks + detailed docstrings
- [x] Add baseline ResNet18 (without SE) for ablation comparison
- [x] Create `backend/ablation_study.py` for side-by-side training comparison

## Frontend (Confidence + PDF Export)
- [ ] Install `jspdf` dependency in frontend
- [ ] Update `frontend/src/Dashboard.js` with circular confidence progress bar
- [ ] Update `frontend/src/Dashboard.js` with PDF export button & generation logic
- [ ] Update `frontend/src/Dashboard.css` with progress bar and export button styles
- [ ] Update `frontend/src/api.js` if needed for new endpoints

