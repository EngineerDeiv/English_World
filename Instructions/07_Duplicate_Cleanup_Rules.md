

## Objective

Maintain a clean knowledge base by removing duplicate entries from all category files inside `./English_Notes`.

This process is independent from categorization.

---

## Scope

Review all `.md` files inside:

```text
./English_Notes
```

Exclude:

```text
./English_Notes/Instructions
```

---

## Duplicate Detection

For every category file:

1. Read the entire file.
    
2. Analyze every table entry.
    
3. Compare each entry against all other entries in the same file.
    
4. Detect duplicated records.
    

A duplicate exists when:

- The word or expression is identical.
    
- The meaning is identical.
    
- The record represents the same entry.
    

---

## Cleanup Process

If a duplicate is found:

- Keep the first occurrence.
    
- Remove all additional occurrences.
    
- Preserve the original formatting.
    
- Preserve alphabetical ordering.
    
- Preserve the existing table structure.
    

---

## Cross-File Duplicate Validation

After processing individual files:

1. Scan all category files.
    
2. Identify entries that exist in multiple categories.
    
3. Determine the correct category according to the categorization rules.
    

If the entry belongs to only one category:

- Keep the canonical occurrence.
    
- Remove all duplicated occurrences from incorrect files.
    

---

## Preservation Rules

Do not:

- Rewrite entries.
    
- Correct grammar.
    
- Translate content.
    
- Modify meanings.
    
- Modify examples.
    
- Modify capitalization.
    
- Reformat tables.
    

Only remove duplicated records.

---

## Canonical Entry Rule

The knowledge base must contain only one canonical occurrence of a word, expression, phrase, idiom, abbreviation, or technical term.

A categorized entry must exist only once in the entire knowledge base.

---

## Final Validation

Before finishing:

1. Verify that no duplicate entries remain.
    
2. Verify that all tables remain valid Markdown tables.
    
3. Verify that alphabetical ordering is preserved.
    
4. Verify that no content was modified except duplicate removal.