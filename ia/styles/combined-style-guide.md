# Combined writing style guide: STE language and Microsoft layout

**Version:** 1.0 · **Date:** October 8, 2026 · **Audience:** writers and AI agents who write technical documents in English

This guide gives one style for technical documents. The language obeys ASD-STE100 Simplified Technical English
(STE). The layout and formatting obey the Microsoft Writing Style Guide. The guide is self-contained. You can
copy it to a different computer or give it to a colleague.

This guide is a summary in our own words. It does not replace the two source documents. Section 13 gives the
sources.

## Contents

1. [Scope and precedence](#1-scope-and-precedence)
2. [Words](#2-words)
3. [Verbs](#3-verbs)
4. [Sentences and paragraphs](#4-sentences-and-paragraphs)
5. [Procedures, notes, and safety instructions](#5-procedures-notes-and-safety-instructions)
6. [Punctuation](#6-punctuation)
7. [Capitalization, headings, lists, and tables](#7-capitalization-headings-lists-and-tables)
8. [Numbers, dates, and units](#8-numbers-dates-and-units)
9. [Formatting of code, UI, and links](#9-formatting-of-code-ui-and-links)
10. [Inclusive and accessible text](#10-inclusive-and-accessible-text)
11. [Example: one text in four styles](#11-example-one-text-in-four-styles)
12. [Checklist before you publish](#12-checklist-before-you-publish)
13. [Sources and tools](#13-sources-and-tools)

## 1. Scope and precedence

**Use this style for technical documents.** Examples are specifications, procedures, runbooks, READMEs,
design documents, whitepapers, reports, analysis memos, and API reference text.

**Do not use this style for these items:**

- Code and code comments.
- Commit messages and chat messages.
- Quoted text and legal text.
- Text in a language other than English.

**For customer-facing UI text, use the Microsoft guide alone.** Examples are button labels, landing pages,
error messages for customers, and alt text. In these items, a friendly tone and contractions are correct.

**If the rules do not agree, use this order:**

1. A rule of your project (for example, a project style sheet) has priority.
2. For language (words, verbs, sentences), STE has priority.
3. For layout and formatting, the Microsoft guide has priority.

The table that follows shows where the two guides do not agree, and the rule of this guide.

| Item | STE | Microsoft guide | This guide |
|---|---|---|---|
| Contractions ("it is" or "it's") | Not permitted | Recommended | Do not use contractions |
| Tone | Neutral and direct | Warm and relaxed | Neutral and direct |
| Sentence fragments | Not permitted | Permitted | Use full sentences, except in headings, labels, and table cells |
| Phrasal verbs ("set up", "log in") | Not permitted | Permitted | Use one verb ("install", "connect") |
| Vocabulary | Approved words and technical terms only | Short, everyday words | Approved words and technical terms only |
| Capitalization | No rule | Sentence case | Sentence case |
| Headings, lists, and tables | No detailed rule | Detailed rules | Microsoft rules |
| Numbers and dates | No detailed rule | Detailed rules | Microsoft rules |
| Code and UI formatting | No rule | Detailed rules | Microsoft rules |

## 2. Words

- **Use one word for one meaning.** Use a word only with its approved meaning and as its approved part of
  speech. For example, "close" is a verb ("close the valve"), not an adjective ("near").
- **Use technical terms of your subject.** You can use a word that is not in the STE dictionary only as a
  technical noun or a technical verb. A technical noun is the name of an item ("pod", "API key"). A technical
  verb is an action of your field ("compile", "deploy").
- **Use the same term for the same item every time.** Do not use synonyms. If you write "application" one
  time, do not write "app" later.
- **Do not use a noun as a verb or a verb as a noun.** Write "examine the data", not "do an examination of
  the data". Write "send an email", not "email the team".
- **Use simple words.** Write "use" (not "utilize"), "try" (not "attempt to"), "start" (not "initiate"),
  "help" (not "facilitate"), "about" (not "approximately").
- **Do not use jargon, slang, or idioms.** A reader who does not know English well cannot translate them.
- **Do not give human qualities to software.** A system does not "think", "want", or "know".
- **Use American English spelling.**
- **Do not use Latin abbreviations.** Write "for example", "that is", and "and other items".
- **Keep noun clusters short.** Use a maximum of three nouns together. For a longer term, write it in full
  one time, then use a short form.
- **Write each acronym in full at its first use.** Put the acronym in parentheses: "time to live (TTL)".
  Do not write the full form of an acronym that all readers know (USB, URL, API). Make the plural with no
  apostrophe: "APIs".

**Approved word or not?** The STE dictionary (section 13) shows the approved words and the words to replace.
The table that follows gives frequent replacements.

| Do not write | Write |
|---|---|
| utilize, leverage | use |
| ensure | make sure |
| perform, carry out | do |
| set up | install, configure, prepare |
| check (as a noun) | examination, test |
| should | must (a requirement) or can (a possibility) |
| in order to | to |
| prior to | before |
| as well as | and |
| a number of | some, many, or the number |

## 3. Verbs

- **Use only these verb forms:** the infinitive ("to start"), the imperative ("Start"), the simple present
  ("starts"), and the simple past ("started"). You can also use the future with "will", and the past
  participle as an adjective ("the installed package").
- **Do not use complex tenses.** Do not write "has been running" or "is collecting". Write "runs" or "ran".
- **Use the "-ing" form only in a technical term** ("load balancing", "rate limiting").
- **Use the active voice.** Write "The collector writes a row", not "A row is written by the collector".
  Use the passive voice only when you do not know who or what does the action.
- **Use the present tense** to describe how a system operates.
- **Start an instruction with a verb.** Write "Restart the pod", not "The pod should be restarted".
- **Do not use phrasal verbs.** Write "install", not "set up". Write "stop", not "shut down".
- **Do not write "you can" when it is not necessary.** Write "Run the script", not "You can run the script".

## 4. Sentences and paragraphs

- **Write short sentences.** A procedure step has a maximum of 20 words. A sentence in descriptive text has a
  maximum of 25 words.
- **Count words like this:** each of these items is one word. The items are a number, a number with its unit,
  an acronym, a hyphenated word, a code element, and text in parentheses.
- **Write one topic in each sentence and in each paragraph.** Start each paragraph with a topic sentence.
  A paragraph has a maximum of six sentences.
- **Put the most important information first.** Start the document with its purpose. Start each section with
  its result or its decision.
- **Do not omit words.** Keep "a", "an", "the", "that", and "who". Write "Select the folder that you want to
  sync", not "Select folder to sync".
- **Use connecting words** to show the relation between sentences: "thus", "but", "then", "if", "because".
- **Use a vertical list for complex text.** If a sentence has more than two "and" or "or", make a list.
- **Make each pronoun refer to one clear item.** Do not start a sentence with "This" or "It" if the reader
  cannot see the item. Write "This command" or "This value".
- **Do not start a sentence with "There is" or "There are".** Start with the subject.
- **Do not put many prepositional phrases one after the other.** Write "the age of the provider snapshot",
  not "the age of the snapshot of the feed of the provider".
- **Put "only" immediately before the word that it modifies.**

## 5. Procedures, notes, and safety instructions

**Procedure steps**

- Use a numbered list. Give the procedure a heading that starts with a verb: "Rotate the API key".
- Write each step as a full sentence in the imperative. Start with a capital letter and end with a period.
- Write one instruction in each step. Write two instructions in one step only if the reader does them at the
  same time.
- If a step has a condition, put the condition first: "If the tag is different, stop the deploy."
- Tell the reader where the action occurs: "In ArgoCD, go to the **mcfo** project."
- Include the last action, for example "Select **Save**".
- Show the result of a step only if the reader must see it: "The status changes to **Synced**."
- For a procedure with one step, write a bullet or a paragraph, not the number 1.
- Put a command that the reader runs in its own code block.

**Notes**

- A note gives information only. A note never gives an instruction.
- Format a note as a bold run-in label: "**Note** The token expires after 90 days."

**Safety instructions**

- Start with the risk level: **WARNING** (risk of injury or of loss of data that you cannot recover) or
  **CAUTION** (risk of damage or of a recoverable loss).
- Then give a clear command. Then give the risk.
- Example: "**WARNING** Do not run `DROP TABLE` on the production database. You cannot recover the data."
- Put a warning or a caution before the step that it applies to, not after it.

## 6. Punctuation

- **Do not use semicolons.** Write two sentences, or make a list.
- **Use the serial comma:** "Redis, TimescaleDB, and the API".
- **Put a comma** after an introductory phrase, and before a conjunction that joins two full sentences.
- **Put a period at the end of each sentence.** Do not put a period or a colon at the end of a heading.
- **Use a colon** at the end of a sentence that introduces a list. After a colon in a sentence, use lowercase.
- **Use an em dash (—) with no spaces.** Use an en dash (–) only for ranges in tables and UI.
- **Do not use a slash for a choice.** Do not write "and/or" or "he/she". Write "or", or write the sentence again.
- **Use hyphens** for words that function as one modifier: "read-only access", "12-second poll".
  Do not put a hyphen after an adverb that ends in "-ly".
- **Use parentheses only** for references, acronyms, item numbers, and step identifiers.
- **Use exclamation points and question marks rarely.** A question mark is correct in a question heading.
- **Put a closing quotation mark** outside a period or a comma, and inside other punctuation. Exception: when
  the punctuation is part of the quoted text.
- **Use one space** after a period, a question mark, or a colon.

## 7. Capitalization, headings, lists, and tables

**Capitalization**

- Use sentence case for all titles, headings, labels, table headers, list items, and link text.
  Capitalize only the first word and proper nouns.
- Use title case only for names of products, services, books, and articles, and for job titles of persons.
- Do not capitalize the full form of an acronym unless it is a proper noun: "time to live (TTL)".
- In code, use the capitalization of the language or the API.
- Do not use all capitals for emphasis. Exception: **WARNING** and **CAUTION**.

**Headings**

- Write short, specific headings. A heading has one line on a phone screen.
- Put the most important word first.
- Use parallel headings at the same level. Start task headings with a verb ("Configure the tunnel").
  Use noun phrases for concept headings ("Data retention").
- Use a lower heading level only for two or more subsections.
- Do not put two headings together with no text between them.
- Do not use "&" or "+" in a heading. Write "and". Use "vs." for a comparison.
- Use heading levels in sequence. Do not skip a level. Do not use bold text in place of a heading.

**Lists**

- Use a bulleted list when the order is not important. Use a numbered list for a sequence or a ranking.
- A list has from two to seven items, if possible.
- Introduce the list with a heading, a full sentence, or a phrase that ends with a colon.
- Make all items parallel. For example, start all items with a verb, or make all items nouns.
- Start each item with a capital letter.
- Put a period after an item only if the item is a full sentence. Do not put a period after items of three
  words or fewer, or after UI labels.
- Do not put a comma, a semicolon, "and", or "or" at the end of an item.
- For a list of terms and definitions, use this format: **Term**. Definition that starts with a capital letter
  and ends with a period.

**Tables**

- Use a table to compare items that have two or more attributes. Do not use a table for a simple list.
- Introduce the table with a full sentence that ends with a period.
- Put the item that identifies each row in the left column.
- Use specific column headers in sentence case: "Provider", not "Name".
- Do not leave a cell empty. Write "None" or "Not applicable".
- Keep the text in each cell short. Put a period in a cell only if the cell has a full sentence.
- Keep the number of columns small, for small screens.
- Align numbers on the decimal point.

## 8. Numbers, dates, and units

- Write zero through nine as words in text: "three providers".
- Use numerals for 10 and more, and for all measurements, percentages, versions, time, and UI values:
  "12 s", "30%", "v2.3.7", "port 8000".
- If a category has one numeral, use numerals for all its numbers: "3, 12, and 25 blocks".
- Write a number at the start of a sentence as a word, or write the sentence again.
- Put commas in numbers of four or more digits: "1,440 cycles". Do not put commas in years, ports, or
  versions.
- Put a zero before a decimal point: "0.25 gwei".
- Use the percent sign with numerals: "45%", not "45 percent".
- Write a range as "from 10 through 15" in text and "10–15" in tables. Do not write "from 10–15".
- Use the minus sign (−) for a negative number.
- Write dates with the full month name: "October 8, 2026". In data, logs, and file names, use ISO 8601:
  `2026-10-08`. Do not write "8th".
- Show the time zone for each time: "14:27 UTC".
- Put a space between a number and its unit ("60 s", "512 MiB"). Exception: "%" and "°".
- Do not use K, M, or B for thousand, million, and billion, unless space is small. Write "1.2 million".

## 9. Formatting of code, UI, and links

The table that follows gives the format of each element.

| Element | Format | Example |
|---|---|---|
| Command, function, method, class, variable, parameter, key, value | Code | `kubectl`, `read_price()`, `image.tag` |
| File name, folder, path, URL in code | Code | `deploy/environments/prod/values.yaml` |
| Environment variable | Code, as typed | `PRICE_STALE_AFTER_S` |
| Command that the reader runs | Code block with a language tag | See the example in section 11 |
| UI label (button, tab, menu, field) | Bold | Select **Sync**. |
| Text that the reader types | Bold, or code if it is a command | Enter **mcfo**. |
| Placeholder | Italic in text, angle brackets in code | Enter *token*. `--who <agent-id>` |
| New term at its definition | Italic, one time | A *pin promotion* is a commit that... |
| Error message in text | Quotation marks | The API returns "feed_stale". |
| Menu path | Bold labels, ">" with spaces | **File** > **Save as** |

- **Use input-neutral UI verbs:** "select", "open", "close", "go to", "enter", "clear", "choose", "move".
  Do not write "click", "click on", "hit", or "press" when a neutral verb is available.
- **Write descriptive link text.** The text must have a meaning without the text around it. Do not write
  "click here", "here", or "read more".
- **Code examples:** give the purpose and the requirements before the code. Show the expected output. Make the
  code easy to copy and run. Test it. Never put a password, a key, or a token in an example.

## 10. Inclusive and accessible text

**Inclusive language**

| Do not write | Write |
|---|---|
| master / slave | primary / replica, main / subordinate |
| whitelist / blacklist | allowlist / blocklist |
| sanity check | quick check, validation |
| dummy value | placeholder value, sample value |
| manpower, man-hours | staff, person-hours |
| he or she, he/she (for any person) | they, you, or the role ("the operator") |
| hang (for software) | stop responding |
| DMZ | perimeter network |

- Use the pronouns that a real person uses. If you do not know them, use "they".
- In examples, use names from different cultures. Do not use stereotypes for roles.
- Do not use places with a political dispute in examples.
- Put the person first: "a user who is blind". Mention a disability only if it is relevant.

**Accessibility**

- Do not use direction alone to show a location ("above", "on the right"). Write "in the table that follows"
  or "on the toolbar".
- Do not use color alone to give information. Also use a word or a symbol.
- Write "and", "plus", and "about" as words. A screen reader can read "&", "+", and "~" incorrectly.
- Give alt text to each image that has a meaning. Tell what the image shows. Do not start with "Image of".
- Write a short description before each table and each diagram.
- Do not put hard line breaks in a sentence.

**Global readers and machine translation**

- Use the word order subject, verb, object.
- Keep "that", "who", and the articles.
- Do not use humor, idioms, or references to one culture.
- Use a verb in a short label if it makes the label clearer: write "Access is denied", not "Access denied".

## 11. Example: one text in four styles

The examples that follow show one runbook section in four styles. The topic is how to verify a deploy.

### Without a style

> **How To Verify A Production Deployment**
>
> Once the pin promotion PR has been merged, the deployment will need to be synced in ArgoCD; it's important
> to note that the app status alone shouldn't be relied upon, since there have been cases (e.g. B38) where the
> app was reported as Synced/Healthy whilst the pods were still running an old image.
>
> 1. Login to ArgoCD and click on the mcfo-workloads app, then hit Sync and wait for it to finish up.
> 2. There is a kubectl command that can be used to get the images: kubectl get pods -n mcfo -o jsonpath='{..image}'
> 3. The tag should be compared against deploy/environments/prod/values.yaml & if they don't match then
>    helm.parameters overrides should be checked for etc.

### STE only

> **How To Verify A Production Deployment**
>
> After you merge the pin promotion PR, sync the application in ArgoCD. The application status does not show
> the image that the pods use. In B38, the status was "Synced" and "Healthy", but the pods used an old image.
>
> 1. Open ArgoCD.
> 2. Select the mcfo-workloads application.
> 3. Select Sync.
> 4. Wait until the sync is complete.
> 5. Get the image of each pod with this command: kubectl get pods -n mcfo -o jsonpath='{..image}'
> 6. Compare the image tag with the tag in deploy/environments/prod/values.yaml.
> 7. If the two tags are different, examine the application for helm.parameters overrides.
>
> NOTE: A helm.parameters override has priority over the values file.

### Microsoft only

> **Verify a production deploy**
>
> After you merge the pin promotion PR, sync the app in ArgoCD. But don't trust the app status by itself. It
> can say **Synced** and **Healthy** while the pods still run an old image. That's what happened in B38.
>
> 1. In ArgoCD, go to the **mcfo-workloads** app and select **Sync**.
> 2. When the sync finishes, list the pod images:
>
>    ```bash
>    kubectl get pods -n mcfo -o jsonpath='{..image}'
>    ```
>
> 3. Compare the tag with `image.tag` in `deploy/environments/prod/values.yaml`. If they don't match, look for
>    `helm.parameters` overrides on the app. An override wins over the values file.

### Combined style (this guide)

> **Verify a production deploy**
>
> After you merge the pin promotion PR, sync the application in ArgoCD. The application status does not show
> the image that the pods use. In B38, the status was **Synced** and **Healthy**, but the pods used an old image.
>
> 1. In ArgoCD, go to the **mcfo-workloads** application.
> 2. Select **Sync**.
> 3. When the sync is complete, get the image of each pod:
>
>    ```bash
>    kubectl get pods -n mcfo -o jsonpath='{..image}'
>    ```
>
> 4. Compare the image tag with `image.tag` in `deploy/environments/prod/values.yaml`.
> 5. If the two tags are different, examine the application for `helm.parameters` overrides.
>
> **Note** A `helm.parameters` override has priority over the values file.

The table that follows shows what each style changes.

| Defect in the first text | STE | Microsoft | Combined |
|---|---|---|---|
| Long sentence with a semicolon | Fixed | Fixed | Fixed |
| Contractions ("it's", "don't") | Fixed | Kept | Fixed |
| Passive voice ("has been merged") | Fixed | Fixed | Fixed |
| Phrasal verbs ("finish up", "log in") | Fixed | Partly fixed | Fixed |
| Two actions in one step | Fixed | Combined on purpose | Fixed |
| Title Case heading | Kept | Fixed | Fixed |
| "click on", "hit" | Fixed | Fixed | Fixed |
| No code or UI formatting | Kept | Fixed | Fixed |
| "&", "e.g.", "etc." | Fixed | Fixed | Fixed |

## 12. Checklist before you publish

**Language (STE)**

- [ ] Each word is an approved word or a technical term of the subject.
- [ ] Each term has one meaning, and each item has one term.
- [ ] Steps have 20 words or fewer. Descriptive sentences have 25 words or fewer.
- [ ] Each paragraph has six sentences or fewer.
- [ ] The text uses the active voice and simple tenses.
- [ ] The text has no contractions, phrasal verbs, Latin abbreviations, or semicolons.
- [ ] Each step has one instruction, and each condition comes before its command.
- [ ] Notes give information only. Warnings and cautions come before their step.

**Layout (Microsoft)**

- [ ] The most important information is first in the document and in each section.
- [ ] Headings use sentence case, are parallel, and have no period, "&", or "+".
- [ ] Lists have an introduction, parallel items, and correct end punctuation.
- [ ] Tables have an introductory sentence, specific headers, and no empty cells.
- [ ] Numbers, dates, units, and ranges obey section 8. Times show the time zone.
- [ ] Code elements use code format. UI labels use bold. Commands are in code blocks.
- [ ] UI verbs are input-neutral. Link text describes its target.
- [ ] The text uses inclusive terms, and images have alt text.
- [ ] Code examples run, and contain no secrets.

## 13. Sources and tools

**Sources**

- ASD-STE100 Simplified Technical English, Issue 9. The specification and its dictionary are free from the
  ASD STE100 maintenance group (<https://www.asd-ste100.org>). The text is under copyright. Do not copy it into
  documents.
- Microsoft Writing Style Guide (<https://learn.microsoft.com/en-us/style-guide/welcome/>).
  The checklists section gives the shortest summary of the rules.

**Tools**

- **Vale** (<https://vale.sh>) is a free prose linter. It has rule packages for the Microsoft and Google styles.
  You can write custom rules for the STE items in section 12.
- **A spelling checker** set to American English.
- **The STE dictionary** in the specification. Use it to find the approved word for each concept.

**Related guides** (use them as references, not as rules):

- Google developer documentation style guide: rules near to the Microsoft guide, with a good word list.
- *The Global English Style Guide* (John R. Kohl): text for translation and for readers who do not know
  English well.
- Diátaxis (<https://diataxis.fr>): how to organize a document set into tutorials, how-to guides,
  reference, and explanation.
- US Federal Plain Language Guidelines (<https://www.plainlanguage.gov>): plain language for the public.
