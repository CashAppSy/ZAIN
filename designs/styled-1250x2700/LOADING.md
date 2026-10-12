# Loading states

| Operation | Feedback | Next outcome |
| --- | --- | --- |
| Number validation | Button spinner + Checking number... | Valid number: SMS; not found or other operator: error modal |
| SMS verification | Button spinner + Verifying code... | Verified: Home; invalid or expired code: stay on verification |
| Google authentication | Google button spinner + Connecting to Google... | Provider authentication; linked number: Home; otherwise link number |
| Network sign-in | Splash spinner + Checking connection... | Securely identified: Home; unavailable/failed: Sign in |

Spinner diameter is 24 design units (approximately 77 pixels in the 1250-pixel export), teal on light backgrounds and white inside cyan buttons. Rotation is linear, 900 ms per revolution. The loading state clears on completion, failure or cancellation; no indeterminate loading should remain after a terminal result. Actual timeout policy belongs to implementation, not these static visual files.

During processing, disable the action button and duplicate submissions. Number fields and conflicting sign-in actions are locked until completion. These are UI specifications; exported pictures do not implement app behavior. The self-contained `loading-demo.html` simulates a 2-second request and disables demo controls. Download and open locally; there is no external service or actual authentication. Animated SVGs contain a rotation animation. PNG/PDF are static.

Splash artwork is an adaptation of the supplied metallic ZAIN/map image, with screenshot status/navigation bars removed. The Arabic tagline and map labels follow the supplied artwork; authentication UI remains English.
