# Categorization Rules

## Categorization Process

For each entry:

1. Analyze the word, phrase, expression, idiom, connector, or term.
2. Determine its linguistic category.
3. Verify whether the category already exists.
4. If the category does not exist, create a new category file.
5. Perform duplicate detection.
6. If no duplicate exists, insert the entry alphabetically.

---

## Duplicate Detection

Before inserting an entry into a destination file:

1. Search the destination file.
2. Search all files inside ./English_Notes.
3. Determine whether the entry already exists.

If an identical entry already exists:

- Do not insert it again.
- Do not modify the existing entry.
- Remove it from Unknown Words.
- Consider the item already categorized.
- Discard the entry if the same word, expression, or phrase already exists in any .md file within ./English_Notes.

If no duplicate exists:

- Insert the entry into the correct category.
- Preserve formatting.
- Preserve alphabetical order.

An entry is considered duplicated when:

- The word or expression is identical.
- The meaning is identical.
- The record already exists in the knowledge base.

The knowledge base must contain only one canonical occurrence of each entry.

---

## Examples

Phrasal Verb → Phrasal_Verbs.md

Regular Verb → Regular_Verbs.md

Irregular Verb → Irregular_Verbs.md

Idiom → Idioms.md

Grammatical Connector, Transition Phrase, Linking Word → Grammatical_Connectors_and_Phrases.md

Technical Term (Cloud, DevOps, AI, ML, Cybersecurity, Networking, Linux, Databases) → Technical_Term.md

Office Vocabulary, Workplace Expression, Business Communication → Office.md

Traffic, Transportation, Driving, Road Expressions → Traffic_City.md

Uncategorized, Generic Vocabulary, Daily Expressions → Miscellaneous.md

Legal, Contract, Compliance, Regulatory, Privacy, or Policy Terms → Legal_Terms.md

Emotional, psychology or feeling word and expressions  → Feelings_and_Emotions.md