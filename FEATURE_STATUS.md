# Feature status — Mental health, nutrition & wellness

| Capability | Status |
| --- | --- |
| Native sidebar and canonical feature registry | Built; 121 pages |
| Shared records, validation, relationships, persistence | Implemented in shared runtime |
| Clickable table rows with centered details popup | Implemented; Edit, Delete, Cancel, keyboard access and mobile layout |
| Domain field forms and source traceability | Imported from static source definitions; historical routes are labeled in mapping |
| CSV exports, attachments, audit and report totals | Implemented |
| At least 15 fictional rows per editable feature | Seeded by startup; measured in reports/seed-verification.json |
| AI question-and-answer workspace | Replaces AI feature tables; questions, context fields, formatted answers, follow-ups and saved history; live provider configuration required |
| Source calculation adapters | Available for explicitly registered calculation variants only |
| Source business-rule and state-machine parity | Incomplete beyond registered adapters and native records; verify each source journey |
| Original account/business data migration | Not performed; source data preserved |
| Provider integrations and external delivery | Not connected; request preparation only |
| Hosted authentication, independent-review roles and tenant isolation | Not migrated; local single-user boundary |

A successful build or populated table is not evidence of full source workflow parity. The source-to-feature map records every extracted definition and route, with explicit exclusions and migration warnings. Test/build reports distinguish checked behavior from remaining work.

| Canonical feature | Native mode | Source entries | Calculators | Status |
| --- | --- | ---: | ---: | --- |
| Clients & customers | records | 0 | 0 | Native records/view |
| Work items & projects | records | 0 | 0 | Native records/view |
| Contacts & parties | records | 3 | 0 | Native records/view |
| Tasks | records | 0 | 0 | Native records/view |
| Calendar | records | 0 | 0 | Native records/view |
| Deadlines & reminders | records | 0 | 0 | Native records/view |
| Notes | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Documents | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Templates | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Invoices & billing | records | 0 | 0 | Native records/view |
| Time tracking | records | 0 | 0 | Native records/view |
| Messages & communications | records | 2 | 0 | Native records/view |
| Reports & analytics | report | 1 | 0 | Native records/view |
| Activity & audit trail | audit | 0 | 0 | Native records/view |
| Provider connections | integration | 0 | 0 | Provider request records only |
| Medications | records | 2 | 0 | Native records/view |
| Physical Therapy | records | 2 | 0 | Native records/view |
| Skin Scanner | records | 2 | 0 | Native records/view |
| Vision Tests | records | 2 | 0 | Native records/view |
| Medical History | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Lab Trend Watch | records | 1 | 0 | Native records/view |
| Feedback | records | 2 | 0 | Native records/view |
| Privacy Policy | records | 1 | 0 | Native records/view |
| Terms of Service | records | 1 | 0 | Native records/view |
| Admin | records | 1 | 0 | Native records/view |
| Advanced advisors | records | 1 | 0 | Native records/view |
| agentic health assistant monitoring tren | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| personalized health coaching generating | records | 1 | 0 | Native records/view |
| medication adherence ai predicting misse | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| symptom to specialist routing with likel | records | 1 | 0 | Native records/view |
| preventive health roadmap by age family | records | 1 | 0 | Native records/view |
| multimodal health dashboard fusing weara | records | 1 | 0 | Native records/view |
| symptom analyzer endpoint | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| medication interaction checker | records | 1 | 0 | Native records/view |
| therapy progress analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| skin lesion vision ai | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| vision test interpreter | records | 1 | 0 | Native records/view |
| medication adherence pattern model | records | 1 | 0 | Native records/view |
| provider portal share data with | records | 1 | 0 | Native records/view |
| prescription pharmacy integration | integration | 1 | 0 | Provider request records only |
| appointment scheduling | records | 1 | 0 | Native records/view |
| telemedicine | records | 1 | 0 | Native records/view |
| insurance information module | records | 1 | 0 | Native records/view |
| lab result import | records | 1 | 0 | Native records/view |
| webhook surface | integration | 1 | 0 | Provider request records only |
| Mood Tracker | records | 1 | 0 | Native records/view |
| Journal | records | 1 | 0 | Native records/view |
| AI Therapy Chat | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Sleep Tracker | records | 1 | 0 | Native records/view |
| Meditation | records | 1 | 0 | Native records/view |
| Breathing | records | 2 | 0 | Native records/view |
| Gratitude Log | records | 1 | 0 | Native records/view |
| Affirmations | records | 1 | 0 | Native records/view |
| Self-Care | records | 1 | 0 | Native records/view |
| Coping Strategies | records | 1 | 0 | Native records/view |
| Goals | records | 1 | 0 | Native records/view |
| Assessments | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Support Groups | records | 1 | 0 | Native records/view |
| Crisis Resources | records | 1 | 0 | Native records/view |
| Find Therapist | records | 2 | 0 | Native records/view |
| Journal Sentiment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Crisis Assessment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Coping Recommendation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Therapist Match | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Sleep Advisor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Mood Trend Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Care integrations | integration | 1 | 0 | Provider request records only |
| Safety plan adherence | records | 1 | 0 | Native records/view |
| Users | records | 1 | 0 | Native records/view |
| Meal plans | records | 2 | 0 | Native records/view |
| Calorie entries | records | 1 | 0 | Native records/view |
| Recipes | records | 2 | 0 | Native records/view |
| Nutrient analyses | records | 1 | 0 | Native records/view |
| Diet recommendations | records | 1 | 0 | Native records/view |
| Food allergies | records | 1 | 0 | Native records/view |
| Grocery lists | records | 2 | 0 | Native records/view |
| Bmi records | records | 1 | 0 | Native records/view |
| Water intake | records | 1 | 0 | Native records/view |
| Supplements | records | 1 | 0 | Native records/view |
| Fitness meal preps | records | 1 | 0 | Native records/view |
| Food substitutions | records | 1 | 0 | Native records/view |
| Fasting schedules | records | 1 | 0 | Native records/view |
| Vitamin checks | records | 1 | 0 | Native records/view |
| Chat history | records | 1 | 0 | Native records/view |
| Nutrition | records | 2 | 0 | Native records/view |
| Ingredients | records | 1 | 0 | Native records/view |
| Categories | records | 1 | 0 | Native records/view |
| Dietary Adjuster | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Grocery Optimizer | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Leftover Suggester | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Nutrition Balancer | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Cooking Timer | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Budget Optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Meal Prep Plan | records | 1 | 0 | Native records/view |
| Verify email | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Dietary restriction mapper | records | 1 | 0 | Native records/view |
| Allergen detection | records | 1 | 0 | Native records/view |
| Seasonal ingredient suggester | records | 1 | 0 | Native records/view |
| nutritionistintheloop meal planning | records | 1 | 0 | Native records/view |
| allergyintolerance profile builder | records | 1 | 0 | Native records/view |
| costminimizing meal planner | records | 1 | 0 | Native records/view |
| cooking skill progression | records | 1 | 0 | Native records/view |
| family meal consensus | records | 1 | 0 | Native records/view |
| restaurant menu decoder | records | 1 | 0 | Native records/view |
| dietaryrestrictionmapper restrictions ing | records | 1 | 0 | Native records/view |
| budgetoptimizer costaware nutrition goals | records | 1 | 0 | Native records/view |
| allergendetection crosscontamination risk | records | 1 | 0 | Native records/view |
| seasonalingredientsuggester | records | 1 | 0 | Native records/view |
| mealprepplan batch cooking recommendation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| meal photo recognition | records | 1 | 0 | Native records/view |
| recipe ratingsreviews route | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| grocery store price api integration | integration | 1 | 0 | Provider request records only |
| barcodeproduct database lookup usda openf | records | 1 | 0 | Native records/view |
| pantry inventory tracking | records | 1 | 0 | Native records/view |
| sharingsocial features | records | 1 | 0 | Native records/view |
| notifications for shopping reminders | records | 1 | 0 | Native records/view |
| Services | records | 1 | 0 | Native records/view |
| Testimonials | records | 1 | 0 | Native records/view |
| Resources | records | 1 | 0 | Native records/view |
| Coaching wellness work | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Recipemanager work | records | 1 | 0 | AI question-and-answer workspace; records available as context |

Row popup verification passed: dashboard and feature rows, keyboard/focus, editing and persistence, delete confirmation/cancellation, centered mobile layout and full-record navigation. See `reports/row-popup-verification.json`.

## Verified local build

Build, API, browser and actual `start.sh` checks passed. All 121 feature pages were visited in the browser; 119 editable tables contain at least 15 fictional rows each. CRUD persistence and mobile layout were checked. Evidence is in `reports/verification.json`, `reports/browser-verification.json` and `reports/startup-verification.json`.

These checks cover the native local workspace. Full source-specific business rules, authentication and live provider operations remain incomplete as described above. Test servers were stopped after verification.

## AI workspace verification

All 28 AI feature routes were checked in the browser and show questions and formatted answers instead of the original record table. Existing records are retained as optional context. Questions, follow-ups, saved history across restart, Markdown tables, safe rendering, downloads, provider-failure recovery and mobile layout passed with a mocked provider. See `reports/ai-workspace-verification.json`.

Live answers require `OPENROUTER_API_KEY` and `OPENROUTER_MODEL` in this app's `.env` and an app restart. No live provider call was made during verification. Conversational answers do not execute unmigrated specialist engines, read record attachments automatically or perform external actions.


## AI word limits

Questions support up to 5,000 words with a live counter and server validation. AI responses and record drafts have a 16,000-token output budget and a default 180-second timeout to support answers up to 5,000 words; actual length depends on the request and model. Answers show their word count, and long questions can be expanded. Browser checks passed for 5,000-word questions and answers, saved history, full downloads, mobile layout and rejection of 5,001-word questions. See `reports/word-limit-verification.json` (mock-provider boundary checks).

## Merged AI assistants

28 original AI entries are now grouped into **6 assistants** in the sidebar. Choose up to 8 related capabilities and add up to 10 questions for one provider request and one saved response. Shared context is sent once; repeated questions are removed after trimming and whitespace/case normalization. The total question limit is 5,000 words and the combined answer target is up to 5,000 words.

Original feature URLs still open the appropriate assistant with that capability selected. Existing records and answers stay in place; the assistant history includes answers saved under its member features. Non-AI record tables retain their popup actions. This merges the assistant workflow and navigation; it does not implement previously missing external integrations or specialist engines. See `reports/assistant-merge-map.json` and `reports/assistant-merge-verification.json`.

## Floating Ask AI assistant

Implemented across this workspace. The bottom-right **Ask AI** button opens a persistent chat panel on every page. Use **Ask AI about item** in a row popup or record view, or **Use current item** inside the panel, to supply the selected record.

- Questions about the page, any explicitly chosen app record, and general topics.
- Formatted answers, comparison tables, follow-ups, copy and Markdown download.
- Conversation and question drafts stay intact during in-app navigation. Saved answers persist in SQLite; the last conversation restores in the same browser tab after reload. The latest 50 saved answers are listed; restoring one displays up to 20 turns. Up to four preceding turns are sent as AI context.
- Up to 5,000 input words and a response budget of up to 5,000 words. Output length remains dependent on the provider and the question.
- Page title and description are supplied automatically; record fields and notes are sent only for a selected item. Attachments and unselected records are not included. **New chat** starts without earlier conversation context.
- Existing AI provider configuration, timeout, rate limit and safe response renderer are reused. The assistant answers and drafts; it does not execute record changes or external actions.

Validation: shared backend tests, all 64 app builds/API checks, and all 64 browser checks passed with an injected test provider. Browser checks cover item context, navigation, saved history/reload, follow-ups, new-chat isolation, error recovery, word limits, keyboard controls, mobile bounds, safe Markdown rendering and attachment refresh. See [verification](reports/floating-ai-verification.json).
