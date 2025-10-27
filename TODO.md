# TODO: Add EV Tracking System with Battery Alerts

## Steps to Complete:
- [ ] Add EV simulation state: array of 3-5 cars with id, battery (100%), location (mock coords), connectedTo (slot id if charging).
- [ ] Add battery discharge logic in sensor interval: decrease battery by 5-15% for cars not charging.
- [ ] Add HTML for battery alert popup: modal div with message, nearest station, mock path, dismiss button.
- [ ] Style popup to match app theme (dark, modern).
- [ ] Integrate popup logic: at battery <=20%, find nearest free slot, show popup with path.
- [ ] Test: Simulate battery drop to 20% and verify popup appears with correct info.
- [ ] Ensure popup is dismissible and doesn't interfere with existing UI.

## Followup Steps:
- Monitor performance and adjust discharge rates if needed.
- Consider adding more features like real-time battery updates or user interaction.
