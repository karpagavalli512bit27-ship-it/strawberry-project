# Video Fix TODO

## Issues
1. Video preview showing on cards (user doesn't want preview)
2. Video not playing when clicked in modal
3. URL encoding not handling all special characters

## Plan
- [x] Read Videos.js and Style.css
- [x] Remove preview `<video>` element from video cards
- [x] Add `useEffect` to programmatically play video when modal opens
- [x] Fix `getVideoSrc` to use `encodeURIComponent` for robust URL encoding
- [x] Test the changes

