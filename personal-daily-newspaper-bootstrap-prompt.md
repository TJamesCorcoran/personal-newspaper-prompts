# Personal Daily Newspaper Bootstrap Prompt

Paste the prompt below into a fresh ChatGPT Work conversation. It is designed to interview the reader before creating anything, turn the answers into a durable editorial charter, test the complete publication workflow, and schedule follow-up calibration.

---

I want you to help me design, test, and establish a personal daily newspaper tailored specifically to me.

The goal is not merely to produce a generic news summary. By the end of this conversation, I want a recurring newspaper whose selection, weighting, intellectual style, tone, length, sources, presentation, and level of serendipity are tuned closely to my preferences.

Do not assume my interests from another person's preferences or from a generic demographic profile. Interview me and build my editorial profile from my answers.

Do not ask me to paste passwords, authentication codes, API keys, deployment secrets, or other credentials into the conversation. Use normal connection and authorization flows when access is required.

## Phase 1: Interview me

Before creating an automation, newspaper, cloud-storage folder, email, or publication helper, conduct a structured editorial interview.

Ask questions in manageable rounds of no more than four questions at a time. Give me clear choices where useful while always allowing a free-form answer. Recommend sensible defaults, but do not silently adopt them. Continue until the consequential choices have been covered.

### Identity, delivery, and privacy

Ask for and confirm:

- The newspaper owner's preferred name.
- The owner's primary delivery email address.
- Any additional recipients and their exact email addresses.
- The desired newspaper and masthead name.
- The desired cloud-storage folder name.
- The owner's time zone.
- Whether each issue should be private and shared directly with named recipients, or unlisted but readable by anyone with the link.
- Whether all recipients should receive a single email containing the confirmed document URL.

Treat these values as configuration supplied during setup. Do not embed personal identifiers, credentials, tokens, folder IDs, project IDs, or deployment URLs in a public template or reusable prompt.

Do not send a test email or change sharing permissions until I approve the completed plan and any required action confirmation has occurred.

### Purpose and reading experience

Ask:

- What I want the newspaper to do for me: inform me, entertain me, expose me to unfamiliar ideas, support my work or hobbies, provide useful conversation material, reduce dependence on social media, or something else.
- How I want to feel while reading it: intellectually stimulated, calm, amused, practically equipped, pleasantly surprised, challenged, reassured, or some combination.
- What publications, writers, newsletters, magazines, podcasts, or websites I particularly like.
- Which voices, styles, publications, or kinds of coverage I dislike.

### Length, schedule, and cadence

Determine:

- Desired delivery time and time zone.
- Which days of the week it should appear.
- Desired reading time and approximate word count.
- Whether weekday and weekend editions should differ.
- Whether I prefer a few long pieces, many short pieces, or a mixture.
- Whether some departments should appear daily, weekly, occasionally, or only when warranted.
- Whether an issue should be shorter rather than padded when the available material is weak.

### Subject areas and relative weighting

Help me allocate approximately 100 editorial points across broad departments. Do not require every category to receive weight.

Possible categories include:

- Major current developments
- Politics, government, law, and public policy
- Economics, business, markets, and institutions
- Technology, computing, and artificial intelligence
- Science, medicine, astronomy, natural history, and the environment
- History, archaeology, language, maps, manuscripts, and material culture
- Literature, publishing, criticism, and the working writer
- Visual art, architecture, music, film, and design
- Home, gardening, farming, animals, food, and cooking
- Craft, machinery, building, woodworking, textiles, and how physical things are made
- Local and regional coverage
- Travel, places, communities, and unusual lives
- Human-interest stories
- Essays, ideas, psychology, and philosophy
- Cabinet-of-curiosities material: beautiful objects, strange facts, neglected papers, old maps, useful charts, and intellectual oddities

Ask for narrower interests within any category I weight highly. Also ask for subjects that should be excluded or covered only rarely.

### Currentness versus evergreen material

Determine the desired proportion of:

- Developments from the preceding one to three days
- Developments from the preceding week or month
- Evergreen essays, history, science, criticism, and discoveries not tied to today's news
- Controlled serendipity: material outside my established interests that you predict I may enjoy

Ask how much surprise I want and how far outside my normal interests you should range.

### Politics and emotional tone

Ask:

- How much politics I want.
- Whether political coverage should emphasize events, policy mechanics, institutions, legal developments, empirical consequences, ideological arguments, personalities, or some mixture.
- My tolerance for partisan framing, controversy, culture-war stories, crime, catastrophe, and disturbing material.
- Whether outrage-driven, anxiety-maximizing, repetitive, or emotionally manipulative stories should be excluded.
- Whether I want advocacy, neutral explanation, competing perspectives, or explicit separation of fact from interpretation.
- Whether I have political, religious, moral, or cultural perspectives that should inform, but not distort, the newspaper.

### Intellectual and analytical style

Determine how much I value:

- Quantitative comparisons and historical baselines
- Causal mechanisms and systems thinking
- Incentives, constraints, tradeoffs, and second-order effects
- Narrative storytelling and individual lives
- Practical advice
- Contrarian arguments
- Conventional expert consensus
- Explicit uncertainty and competing explanations
- Technical detail
- Accessible explanation
- Humor, wit, sentiment, or a more austere tone

Ask whether numerical claims should normally answer “compared with what?” by providing prior values, longer trends, suitable comparators, scale, and practical significance.

### Sources

Ask about:

- Preference for primary sources, research papers, official data, specialist publications, expert blogs, mainstream reporting, magazines, and archives.
- Whether paywalled sources are acceptable.
- How source-rich the paper should be.
- Whether every factual article should contain direct descriptive links near the claims they support.
- Whether the newspaper should be self-contained enough that I rarely need to open links.
- Whether popular reporting should be treated as a lead that is followed into primary research for substantial science, medical, economic, or policy articles.

### Local and personal context

Ask about:

- Where I live and which local or regional areas matter to me.
- My profession, projects, responsibilities, hobbies, household, and recurring practical interests.
- Topics in recent conversations that are actually work assignments, errands, or one-time questions rather than genuine interests.
- Whether you may use my recent conversations as interest signals.
- Which recurring personal projects deserve continuing coverage.

Do not confuse a single administrative lookup with a lasting editorial preference.

### Presentation

Determine preferences for:

- Newspaper or magazine style
- Masthead and section naming
- Native document formatting
- Headline style
- Images, maps, charts, diagrams, tables, captions, and credits
- Article length and page rhythm
- Bullets versus narrative prose
- A short editor's note
- A front-page digest
- A main feature
- Regular departments
- A closing section or clean ending

Ask whether source-derived images should be used only when informative rather than decoratively.

### Repetition and portfolio balance

Ask:

- How quickly a topic may recur.
- Whether follow-up stories should appear only after a material development.
- How aggressively same-issue redundancy should be eliminated.
- Whether enthusiasm for one successful topic should increase its frequency or merely inform how that topic is treated.
- Whether the paper should enforce broad subject diversity across each week.

## Phase 2: Produce an editorial charter

After the interview, synthesize my answers into a concise but complete editorial charter.

Include:

- Purpose
- Intended reading experience
- Schedule and length
- Subject-weight table totaling approximately 100 points
- Current-versus-evergreen mixture
- Serendipity setting
- Tone and emotional boundaries
- Politics policy
- Analytical style
- Source policy
- Local and personal context
- Presentation rules
- Repetition and portfolio rules
- Explicit inclusions
- Explicit exclusions
- Distribution and privacy settings

Identify any contradictions or unresolved decisions. Ask me to revise or approve the charter.

Do not build the recurring automation until I approve it.

## Phase 3: Design the newspaper workflow

After approval:

1. Verify that the necessary cloud-storage and email connections are available for the owner account. If a connection or authorization is missing, stop and guide me through connecting it.
2. Create the approved top-level newspaper folder.
3. Record the resulting folder ID only in the private operational configuration that needs it. Do not include it in a public template.
4. Draft the durable scheduled-task prompt using the entire approved editorial charter. Important preferences and constraints must be written explicitly into the task prompt; do not rely on vague conversational memory.
5. Name each issue exactly `{{NEWSPAPER_NAME}} — YYYY-MM-DD`, substituting the approved newspaper name and issue date.
6. Move each issue into the newspaper folder and verify that it is there.
7. Format the issue semantically with native document styles:
   - Title for the masthead
   - Subtitle or restrained italic styling for the date, deck, or editor's note
   - Heading 1 for departments
   - Heading 2 for article titles
   - Heading 3 only for genuine subsections
   - Readable paragraphs, spacing, lists, tables, captions, and descriptive hyperlinks
   - Consistent headline and body colors
   - Source-derived images only when they add information
8. Make the newspaper self-contained while preserving direct links to important sources.
9. Clearly distinguish facts, interpretation, uncertainty, and speculation.
10. Create the recurring scheduled task at the approved time and cadence. Keep it in this setup conversation if supported so later tuning can retain context.

## Phase 4: Establish reliable publication and email delivery

Do not assume that creating the document means it was published.

The complete workflow must cover:

- Document creation
- Correct folder
- Correct sharing permissions
- Permission verification
- Email to every approved recipient
- Verification that the email was actually sent

If I choose private distribution, directly share the document with the approved accounts at the approved access level and email the verified link to the approved recipients.

If I choose “Anyone with the link — Viewer” and the ordinary storage connector cannot create anonymous link access, do not quietly weaken the requirement to organization-only or named-user sharing.

Instead, help me create a small publication helper using the storage provider's supported automation platform. For Google Drive, a Google Apps Script helper should:

- Be owned by the newspaper owner's account.
- Store the actual folder ID only in its private configuration.
- Store approved recipient addresses only in its private configuration.
- Search only the configured newspaper folder.
- Require the exact title `{{NEWSPAPER_NAME}} — YYYY-MM-DD`.
- Require exactly one matching native document.
- Set `DriveApp.Access.ANYONE_WITH_LINK` and `DriveApp.Permission.VIEW`.
- Verify the resulting access and permission before sending email.
- Email the confirmed document URL to every approved recipient.
- Check remaining mail quota before sending.
- Store an idempotency property keyed by issue date so it cannot email the same issue twice.
- Run only during an approved publication window in the owner's time zone.
- Use an installed time-based trigger, such as every ten minutes during the publication window.
- Notify the owner promptly if the trigger fails.

Prefer an installed trigger over a public Web app. Do not deploy an `/exec` endpoint unless the helper actually contains a deliberately designed and secured `doGet()` or `doPost()`. If an endpoint is created, protect it with appropriate authentication or a secret, restrict it to files inside the configured folder, and never commit its secret to version control.

Guide me through authorization and trigger installation one step at a time.

The newspaper task should create and place the document. The publication helper should own anonymous sharing, permission verification, and recipient email.

## Phase 5: Test before enabling daily production

Before treating the system as complete:

1. Generate one representative test issue using the approved charter.
2. Let me inspect it and provide corrections.
3. Revise the charter and scheduled-task prompt as necessary.
4. Create the native document.
5. Verify the folder.
6. Run or wait for the publication helper.
7. Verify the actual storage permission metadata.
8. Verify that one email was sent to all approved recipients with the real document URL.
9. Confirm that the link opens with the intended access level.
10. Only then enable the recurring task.

Never report publication as successful merely because the newspaper text was generated.

## Phase 6: Mandatory tuning review

A personalized newspaper should be calibrated from observed issues, not merely from an initial questionnaire.

After enabling the newspaper, create a one-time follow-up in this same conversation after the third delivered issue. Ask me to evaluate:

- Overall quality from 1–10
- Best article and why
- Weakest article and why
- Subjects receiving too much coverage
- Subjects receiving too little coverage
- Whether the weighting feels right
- Whether articles are too long, too short, or appropriately varied
- Whether the newspaper is too current, too evergreen, or properly balanced
- Whether it is too predictable or too random
- Whether the tone is too dry, too chatty, too earnest, too negative, or otherwise wrong
- Whether the analysis is deep enough
- Whether numerical comparisons and baselines are adequate
- Whether source links are useful
- Whether images, tables, maps, or charts are helping
- Whether stories or mechanisms are being repeated
- Which article I would have cut
- Which kind of article I wished had appeared
- Any new explicit inclusion or exclusion rules

Convert my feedback into concrete revisions to the editorial charter and the actual recurring task prompt. Show me the proposed changes before applying them.

Schedule a shorter second tuning review after approximately the seventh issue unless I decline. Remind me that I can provide instructions such as:

- “More of this, but do not increase the topic's frequency.”
- “Reduce this department from 15% to 5%.”
- “This was relevant but analytically conventional; shorten pieces like it.”
- “Use more primary research.”
- “Give me more historical baseline.”
- “Stop covering this topic.”
- “Increase controlled serendipity.”
- “Make weekends slower and more literary.”
- “This story was work-related, not a personal interest.”
- “Update the newspaper charter with this preference.”

## Operating principles

Throughout the setup:

- Interview first; do not guess.
- Do not reproduce another person's editorial tastes.
- Offer defaults, but make consequential choices explicit.
- Keep questions manageable.
- Preserve strong dislikes and exclusions as hard constraints.
- Translate preferences into durable operational rules.
- Test the complete delivery chain.
- Verify external actions rather than assuming they succeeded.
- Treat the first week as calibration.
- Encourage continued tuning as interests and circumstances change.
- Keep credentials and private operational identifiers out of reusable prompts, public files, logs, and version control.

Begin with the first round of no more than four interview questions. Do not create anything yet.

