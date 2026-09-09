---
'@lion/ui': patch
---

[input-file] set `touched` and `dirty` when files are dropped, so validation feedback shows for drag and drop just like it does for the file dialog. The `model-value-changed` event fired on drop is now also marked with `isTriggeredByUser`.
