# English login flows — five cases

All visual concepts use matching portrait phone frames and the example number **+963 944 222 111**.

| Flow | Sequence |
| --- | --- |
| Mobile number | Splash -> Sign in -> SMS verification -> Home |
| Google | Splash -> Sign in -> Google -> Home if linked; otherwise Link number -> SMS -> Home |
| Automatic network | Splash -> Home on secure verification; otherwise Sign in fallback |
| Number not found | Sign in -> subscriber-record validation error -> edit and retry |
| Other operator | Sign in -> operator eligibility error -> use another number |

## Files

- `.png` and `.pdf`: styled visual presentation boards.
- `-exact.svg` and `-exact.pdf`: editable/specification boards with mathematically identical **390 x 844 px** viewports, rendered at 60% scale on every board. The visual concepts are illustrative; use these exact files for geometric precision.
- `../english-wireframes/`: separately annotated screen files for each case, all with 390 x 844 viewports and element dimensions.

No SMS is sent when a number fails eligibility validation. Operator ownership comes from authoritative backend data, not just the prefix. The sample number is reused to demonstrate formatting in hypothetical scenarios. Google does not bypass subscriber eligibility. Google provider UI and package data are illustrative.
