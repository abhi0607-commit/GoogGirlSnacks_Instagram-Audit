# Good Girl Snacks — Instagram Audit & Redesign (portfolio site)
This project is an Instagram audit and redesign for Good Girl Snacks, presented as a portfolio case study website.

It starts by auditing the brand's current Instagram profile, then proposes a refreshed presence:

* Bio makeover comparing the current bio with the improved one
* Full proposed profile mockup with a phone preview and a pinned-post triptych
* Story highlight covers in a consistent visual style
* Reel storyboard, a packed-lunch pickle reel planned frame by frame
* Retail journey, showing how a shopper moves from the store aisle to the store locator

Project Link: https://claude.ai/artifact/AHHUM3M3ARFYZtdXKnwKxp

Static HTML/CSS/JS. No build step, backend, login, or API key.

## Run locally
    cd good-girl-snacks-site
    python3 -m http.server 8000
    # open http://localhost:8000
(Or double-click index.html. A local server is recommended so the video and images load the same way they will when hosted.)

`index.html` is the site. `artifact.html` is the same page without the outer html/head/body tags, used for the claude.ai preview.

## Swap assets (keep the file names, or update the src in index.html)
| File in assets/ | Used for | Source |
|---|---|---|
| hero-cover.jpg | Hero artwork | Good Girl Snacks Instagram Redesign.png |
| original-profile-crop.jpg | Audit evidence | Original IG screenshot, cropped; "Followed by" row removed |
| original-profile-full.jpg | Spare full-length version, same crop rule | Original IG screenshot |
| brand-avatar.jpg | Avatar in comparison + profile mockup | Cropped from the screenshot |
| bio-makeover.jpg | Static fallback under the comparison | Good Girl Snacks bio makeover.png |
| highlight-covers.jpg | Highlights section | Good Girl Snacks highlight covers.png |
| reel-storyboard.jpg, reel-frame-1..3.jpg | Reel storyboard (frames are crops of the board) | Packed lunch pickle reel storyboard.png |
| aisle-to-locator.jpg, journey-step-1..3.jpg | Retail journey (steps are crops of the graphic) | From the aisle to the locator-1.png |

Not supplied, built in HTML instead: full proposed-profile mockup (phone in section 3 / "View full proposed profile"), pinned-post triptych (three tiles in section 3).
