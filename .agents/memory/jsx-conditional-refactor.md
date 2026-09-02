---
name: Conditional report views
description: Durable guidance for maintaining the report overview and detail-view JSX.
---

Large, repeated report sections are safest when each detail view has one clearly paired conditional wrapper and its closing tag is kept adjacent to the section.

**Why:** Broad edits to repeated JSX can attach a closing tag to the wrong section while still looking visually plausible; the resulting failure is only obvious at compile time.

**How to apply:** When changing report navigation or section visibility, edit one section boundary at a time and run the Office Assistant typecheck before continuing.