You are Codex, acting as a world-class Principal Product Designer, Senior UI/UX Architect, and Staff/Principal Full-Stack Engineer with 20+ years of experience shipping premium consumer software.

Your mission is to transform this repository into a stunning, original, production-grade modular media application inspired by the clarity, cinematic immersion, and usability level of apps like Stremio, Apple TV, Plex, and Netflix — but NOT a clone. It must have its own identity, premium visual language, and a clean lawful add-on architecture that I can extend later with my own add-ons.

You are allowed to think deeply, inspect the full repository, make architectural decisions, refactor aggressively where justified, create and edit files, run builds, run tests, fix errors, and iterate until the result is clean, stable, fast, and commercially polished.

CRITICAL EXECUTION MODE
- Do not stop at analysis.
- Do not give me generic advice only.
- Audit the repo, create a smart plan, and implement it.
- Use parallel sub-tasks where useful:
  1. UI/UX audit and redesign
  2. architecture and add-on system
  3. performance and state management
  4. build/test/fix pass
- Reuse existing environment variables, config, tokens, and project settings already present in the repository or environment. Do not ask me to manually rediscover values that already exist.
- Preserve working functionality unless there is a strong reason to replace it.
- If the codebase has weak structure, duplicated logic, poor styling, dead code, slow rendering, broken flows, or inconsistent UX, fix it properly.
- Make strong autonomous decisions when needed.
- Prefer disciplined, elegant engineering over flashy hacks.
- Build something that feels expensive, intentional, stable, and investor-grade.

NON-NEGOTIABLE PRODUCT GOAL
Create a premium modular media center with:
- breathtaking cinematic UI
- elegant navigation
- excellent discovery and search UX
- polished details page
- immersive player shell
- library/watchlist/continue-watching flows
- robust future-proof add-on architecture
- excellent responsiveness and accessibility
- high performance
- senior-level code quality

IMPORTANT LEGAL / PRODUCT BOUNDARY
- Do not hardcode or preinstall shady, unofficial, or legally questionable sources.
- Do not build piracy-oriented defaults.
- Build a lawful, modular shell and extension framework only.
- Add mock/demo providers using placeholder or lawful sample data so the architecture is fully testable right now.

DESIGN VISION
The final app must feel:
- premium
- dark
- cinematic
- minimal
- sharp
- original
- addictive
- modern
- very high taste
- smoother and more refined than most open-source media apps

VISUAL DIRECTION
Create a premium design system with:
- deep blacks, graphite surfaces, subtle glass, tasteful contrast
- large cinematic art surfaces balanced with minimal chrome
- beautiful typography hierarchy
- elegant spacing rhythm
- sophisticated cards that feel tactile and expensive
- premium hover, focus, pressed, selected, loading, and disabled states
- high-quality skeleton loaders
- gorgeous search bar and filters
- original icon treatment
- subtle motion design that feels smooth and intentional, never gimmicky
- clean responsive behavior across the current target platforms
- strong RTL-readiness and internationalization foundations where feasible

UX REQUIREMENTS
Optimize for:
- instant clarity
- low cognitive load
- fast discovery
- intuitive navigation
- obvious primary actions
- clear install/manage add-on flows
- elegant empty states
- useful onboarding or first-run setup if appropriate
- keyboard navigation
- accessibility
- polished error states
- seamless continue-watching and watchlist experience
- settings users can actually understand

INFORMATION ARCHITECTURE
Design and implement the app around these core areas where appropriate:
- Home
- Discover / Explore
- Search
- Content Details
- Player
- Library
- Watchlist
- Continue Watching
- Add-ons
- Settings
- Optional onboarding / first-run experience

HOME SCREEN
Build a premium homepage with:
- cinematic hero area
- content rails
- continue watching
- recently added
- trending / recommended / genres if applicable
- excellent hierarchy
- fast scanning
- beautiful navigation
- no clutter

DETAILS PAGE
Create an exceptional details page:
- premium poster/backdrop composition
- clear metadata
- synopsis
- tags / badges / quality indicators
- strong CTA hierarchy: play, resume, add to watchlist
- sections for related content / episodes / cast if supported by data
- elegant fallback states when data is incomplete

PLAYER SHELL
Implement a premium playback experience:
- immersive layout
- elegant controls overlay
- keyboard shortcuts
- fullscreen support where relevant
- progress persistence hooks
- subtitle/audio hooks in architecture
- polished unavailable-source and playback-error states

ADD-ON / PLUGIN ARCHITECTURE
This is one of the most important parts.

Design and implement a clean modular add-on system so I can integrate my own add-ons later.

Requirements:
- add-on manager screen
- install / enable / disable / remove flow
- local manifest-based registration
- typed interfaces for providers
- normalized contracts for data
- capability-based add-on model
- clear separation between core app and provider implementations
- hooks/interfaces for:
  - catalog providers
  - metadata providers
  - stream providers
  - subtitle providers
  - search providers
- robust error isolation so one broken add-on cannot break the app
- adapter pattern or equivalent clean abstraction
- mock/demo add-ons using lawful placeholder data
- concise developer-facing documentation explaining how new add-ons plug in later

TECHNICAL STANDARDS
First inspect the actual stack and adapt intelligently.

Rules:
- if the current stack is solid, improve it instead of rewriting for ego
- if the current architecture is badly broken, migrate only with strong justification
- maintain or improve build reliability
- use strong typing
- keep components reusable and coherent
- separate UI, domain logic, and add-on infrastructure clearly
- unify styles, spacing, typography, radii, shadows, and layout behavior
- eliminate dead code and duplication
- prefer readable, maintainable, production-level code

If appropriate to the existing repo, prefer:
- TypeScript
- React / Next.js / Vite / Electron alignment with the existing project
- clean design system approach
- reusable UI primitives
- sound state management
- lazy loading and code splitting
- debounced search
- request cancellation where relevant
- caching where useful
- reduced re-renders
- smooth rendering for long lists
- resilient error boundaries

PERFORMANCE GOALS
Make the app feel fast and premium:
- optimize first meaningful paint where possible
- reduce unnecessary re-renders
- improve image handling
- lazy-load heavy routes/components
- optimize content rails and large lists
- minimize layout shift
- keep interaction latency low
- make search responsive
- keep navigation smooth

ACCESSIBILITY + QUALITY
Implement serious polish:
- semantic structure
- accessible labels
- strong focus visibility
- keyboard support
- contrast awareness
- responsive layout discipline
- empty states that guide action
- complete loading states
- complete error states
- no janky transitions
- no half-finished UI
- no obvious placeholder junk

CODEX-SPECIFIC EXECUTION
Work in phases and keep momentum:
1. inspect the repo thoroughly
2. identify weaknesses and bottlenecks
3. produce a concise implementation plan
4. execute the redesign and refactor
5. run build / lint / tests where available
6. fix errors and regressions
7. deliver a concise implementation summary

When useful, split work into parallel threads/subtasks, but keep one coherent architecture and one consistent design language. Avoid fragmented outcomes.

OUTPUT EXPECTATIONS
At the end, provide:
- concise summary of what changed
- architecture decisions
- main files changed
- how the add-on system works
- how I can plug in my own add-ons later
- any optional next-step improvements

QUALITY BAR
This must not look like a hobby clone.
It must feel like a serious premium startup product.
It must impress a demanding founder with strong taste.
It must be visually memorable, technically clean, and commercially believable.

START NOW
Begin by scanning the full repository, understanding the current architecture, then execute the strongest end-to-end upgrade path without unnecessary back-and-forth.