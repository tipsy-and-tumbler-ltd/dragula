# 1.1.4 Fog Creek

- Added `'shadow'` event to enable easy updates to shadow element as it's moved

# 1.1.3 Drag Queen

- Fixed a bug where `dragula` wouldn't make a copy if the element was dropped outside of a target container
- If a dragged element gets removed for an instance that has `copy` set to `true`, a `cancel` event is raised instead

# 1.1.2 Eavesdropping

- Fixed a bug where cancellations that ended up leaving the dragged element somewhere other than the source container wouldn't trigger a `drop` event

# 1.1.1 Slipping Jimmy

- Fixed a bug where the movable shadow wouldn't update properly if the element was hovered over the last position of a container

# 1.1.0 Age of Shadows

- Added a movable shadow that gives visual feedback as to where a dragged item would be dropped
- Added an option to remove dragged elements when they are dropped outside of sanctioned containers
- Added an option to revert dragged elements back to their source container when they are dropped outside of sanctioned containers

# 1.0.1 Consuelo

- Removed `console.log` statement

# 1.0.0 IPO

- Initial Public Release
