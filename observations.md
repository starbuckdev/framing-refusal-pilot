# Observations (uncontrolled)

These are informal observations from pilot testing. They are not part
of the data matrix and are not used to test any hypothesis. They are
recorded to show how the design was developed.

## 1. Ebola pilot, October 2026
In fresh chats, DeepSeek and Claude each answered an Ebola infectious
dose question in both analytical and goal-directed wording, with no
refusal and no appended warning. This ran before the prompts were
frozen, with wording that differed from the frozen prompts. The cells
are marked as pilot-informed in predictions.md. Details are in
data/pilot_log.csv.

## 2. Interface pause on a follow-up message
In a Claude chat that had already answered the Ebola prompts, I sent a
follow-up message asking to reframe the question. The interface paused
the chat and required me to edit my message before continuing. I did not
capture the interface wording. My hypothesis is that rewording language
was treated as an attempt to bypass a filter, but this is a guess, and
the cause could also have been a limit or an error. This is why the
protocol sends one prompt per fresh chat, with no follow-ups, and why
interface blocks are coded separately (B) from model refusals.

## 3. Usage limit on logged-out ChatGPT
Logged-out ChatGPT stopped accepting prompts after three in one session.
The main run may need to span several sessions or days for that product.
The access method will be recorded for every response.

## 4. Caffeine pilot, October 2026
DeepSeek and ChatGPT were each run on several caffeine prompt variants
that differed from the frozen wording (lethal vs. dangerous, first
person vs. third person, and a version that appealed to the literature).
Both models answered some variants and ChatGPT declined others. These
runs informed the final prompt wording and are marked as pilot-informed
in predictions.md.

## Storage
Full response text for all pilot and main runs is kept privately and is
not published.
