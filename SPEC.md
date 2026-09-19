# Yunyi Qian — Marketing Portfolio

Status: Draft specification. Product direction agreed; proposed testing approach awaits confirmation. Issue-tracker publication pending configuration.

## Problem Statement

Yunyi Qian needs a clear, professional portfolio that helps employers assess her experience in social media, performance marketing, and creator marketing. The website should foreground past projects, individual contributions, strategic decisions, and measurable results. Its presentation should suit a marketing student rather than an art portfolio.

## Solution

Create a polished, minimal, editorial single-page portfolio with Introduction, Selected Work, About, and Contact sections. Present three projects directly on the page using spacious stacked sections. Each project includes a title, role, concise description, and two or three supported highlights. Employers should be able to understand each project in approximately 20 seconds without opening a separate case study.

Use the agreed headline: “Turning audience insights into content, campaigns, and growth.” Introduce Yunyi as a digital social media student focused on social media, performance marketing, and creator marketing.

## User Stories

1. As an employer, I want to see Yunyi's name immediately, so that I know whose work I am reviewing.
2. As an employer, I want to understand her marketing focus, so that I can assess relevance to my open role.
3. As an employer, I want to reach Selected Work from the introduction, so that I can quickly review her experience.
4. As an employer, I want to see all three featured projects on one page, so that I can compare them without repeated navigation.
5. As an employer, I want to see the role attached to each project, so that I can distinguish her contribution from team outcomes.
6. As an employer, I want concise descriptions of her actions, so that I can understand her practical skills.
7. As an employer, I want clearly presented results, so that I can assess the impact of her work.
8. As an employer, I want to understand her TikTok LIVE operations experience, so that I can evaluate her commerce and optimization skills.
9. As an employer, I want to understand the Bowlcut strategy change, so that I can evaluate her marketing judgment.
10. As an employer, I want to see her team leadership experience, so that I can assess her ability to collaborate and lead.
11. As an employer, I want to understand her audience analysis and A/B testing experience, so that I can evaluate her analytical approach.
12. As an employer, I want to see her undergraduate and graduate education, so that I can understand her academic background.
13. As an employer, I want a clear email contact action when her address is supplied, so that I can discuss opportunities.
14. As an employer, I want access to her LinkedIn profile when supplied, so that I can review her professional background.
15. As an employer, I want access to her résumé when supplied, so that I can review her qualifications in a familiar format.
16. As a mobile visitor, I want a readable layout without horizontal scrolling, so that I can review the portfolio on my phone.
17. As a keyboard user, I want usable navigation and visible focus, so that I can access every available action.
18. As a visitor using enlarged text, I want content to remain readable and accessible, so that I can review the work comfortably.
19. As Yunyi, I want my approved palette used consistently, so that the portfolio has a cohesive visual identity.
20. As Yunyi, I want the initial design to work without project images, so that missing materials do not block progress.
21. As Yunyi, I want only supported claims included, so that the portfolio accurately represents my experience.

## Implementation Decisions

- Use a single public-facing page composition with Introduction, Selected Work, About, and Contact in that order. A separate Work gallery was discussed earlier and superseded by the accepted single-page recommendation.
- Use in-page navigation with descriptive labels and semantic section structure.
- Use polished editorial typography, generous spacing, restrained accents, and spacious stacked project presentations. Prioritize text and results; project imagery is deferred.
- Use Parchment (#f1f0ea) for the main background, Shadow Grey (#2d232e) for headings and primary buttons, Bone (#e0ddcf) for section surfaces, and Gunmetal (#474448) or Taupe Grey (#534b52) for supporting text. Check contrast for actual foreground/background combinations.
- Name: Yunyi Qian.
- Education: University of Wisconsin–Madison, undergraduate studies in Communication Arts; University of Southern California (USC), graduate studies in Digital Social Media. Exact degree names, graduation dates, and completion status have not been provided; do not invent them.
- Feature these projects using supplied facts:
  - **Scaling TikTok Shop LIVE** — **TikTok LIVE Operations Intern**. Managed seller LIVE operations and used real-time performance data to optimize traffic, content, product strategy, and conversion, driving **$10K+ GMV in three hours**. Do not relabel GMV as profit or personal earnings.
  - **Bowlcut: Building Brand Awareness Through TikTok** — **Team Lead & Account Executive**. Led a **four-person team** and shifted the client strategy from conversion-first to awareness-first through TikTok content, creator seeding, campus activations, and paid media. No quantitative campaign outcome was supplied.
  - **Data-Driven Social Media Growth** — **Trends Group, Media Management & Analytics Intern**. Used audience analysis and A/B testing to optimize social campaigns, increasing **Douyin and WeChat views by 23%** and **engagement by 18%**. Do not invent platform-specific breakdowns or a measurement period.
- Make email the primary contact action, with LinkedIn and résumé as secondary links once supplied. During the draft, use clearly identified unavailable states or placeholders without fabricated addresses, destinations, or downloads.
- Include responsive behavior, semantic headings, visible keyboard focus, readable contrast, descriptive page metadata, and a palette-matched favicon.
- A static presentation is sufficient; no database, account system, or custom backend is needed. The exact implementation stack is not a user requirement.

## Testing Decisions

- **Proposed seam, awaiting user confirmation:** validate the rendered page through browser-level checks. This is the highest useful boundary for a static portfolio and covers behavior employers actually encounter.
- Test externally observable behavior rather than component structure, CSS class names, or implementation details.
- Cover section navigation, project facts and metrics, education text, available contact destinations, and the absence of misleading active placeholder links.
- Check desktop and narrow mobile layouts for readability, clipping, and unintended horizontal scrolling.
- Check keyboard navigation, visible focus, logical heading order, and usability at 200% text enlargement.
- Verify that all referenced local assets load and that the page has the correct title and description.
- The project folder had no implementation, testing framework, glossary, or ADRs at inspection. There is no existing test prior art to reuse. Prefer a small browser acceptance checklist over introducing a test framework solely for this static page.

## Out of Scope

- Individual case-study pages and a separate Work gallery for this version.
- Art-gallery presentation or image-led project treatments.
- Creating or gathering project screenshots, photographs, and other deferred materials.
- Inventing campaign outcomes, project dates, degree details, contact information, or a résumé.
- Blog, CMS, filtering, search, authentication, persistent storage, uploads, and contact-form backend.
- Additional marketing integrations, analytics tracking, and paid services.

## Further Notes

- The user accepted the recommended structure, project presentation, headline, and contact hierarchy.
- Contact details, LinkedIn URL, résumé, and project materials can be supplied later. These remain content dependencies for a fully actionable employer-facing version.
- The prior build attempt registered a private Site but did not publish a version. Preserve its identity when implementation resumes; do not register a duplicate.
- The current request is specification synthesis; website implementation and publication are paused.
- Issue-tracker configuration is unavailable. Run `/setup-matt-pocock-skills` to configure the destination before publishing this specification with the `ready-for-agent` label.
