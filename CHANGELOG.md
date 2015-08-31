1.0.6 patched

changelog:
- line#413 Select inputs closes on fast tap since issue: https://github.com/ftlabs/fastclick/issues/268, https://github.com/percolatestudio/fastclick/commit/9ac88ef4653cb1621644ce58080c0696ef9a6598, https://github.com/ftlabs/fastclick/pull/340
- line#302 Fire mousedown/mouseup Events on iOS, https://github.com/ftlabs/fastclick/pull/308

- Prevent syntetic events to bubble: https://github.com/ftlabs/fastclick/pull/346
- Focus on SVG elements on android: https://github.com/ftlabs/fastclick/pull/418
- No syntetic click to editable content areas: https://github.com/ftlabs/fastclick/pull/381
- IE10 typo fix: https://github.com/ftlabs/fastclick/pull/375
- focused fields on iOS: https://github.com/ftlabs/fastclick/pull/361
- Added stopPropagation() to handle the case where both touchend AND click listeners have been defined, https://github.com/ftlabs/fastclick/pull/341/files
