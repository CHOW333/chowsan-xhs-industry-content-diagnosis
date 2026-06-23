# Obsidian Sync Pattern

This public skill must not assume a private local vault path.

If the user wants Obsidian output, ask for or infer:

- Vault root.
- Project folder name.
- Whether to create `workflow` and `cases` subfolders.

Recommended structure:

```text
Vault/
└─ ProjectName/
   ├─ Home.md
   ├─ Case Index.md
   ├─ Workflow/
   │  ├─ 01_Workflow.md
   │  ├─ 02_Output Template.md
   │  ├─ 03_Rule Library.md
   │  └─ 04_Update Log.md
   └─ Cases/
      └─ YYYY年M月D日_Industry.md
```

Rules:

- One industry case equals one Markdown file.
- Put reusable workflow documents in the workflow folder.
- Put concrete industry cases in the cases folder.
- Update the case index after creating a new case.
- Update the rule library only when a new reusable pattern appears.
- Do not overwrite existing files without checking.
