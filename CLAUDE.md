# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is the Industry Commons for Defense (ICD) Artifacts repository, containing legal and governance documents for defense technology collaboration. This is NOT a software development repository - it is a document repository containing templates, licenses, and governance frameworks.

## Repository Structure

The repository contains plain text documents organized into five directories:

1. **licenses/** - SW-ICD, HW-ICD, Data-ICD, and Model-ICD licenses defining terms for different artifact types
2. **templates/** - CRDS (Capability Requirements Data Sheets), HRDS (Hardware Requirements Data Sheets), and operational templates
3. **governance/** - Charters, protocols, and disclosure frameworks
4. **technical/** - Metadata schemas, audit ledger formats, and testing guidance
5. **operational/** - Field deployment guides, partner onboarding, and operational playbooks

## Working with Documents

### Document Naming Convention
- License files: `{Type}-ICD_License_v{version}_{date}.txt`
- Templates: `ICD_{Type}_Template_v{version}_{date}.txt`
- Other documents: `ICD_{Description}_{version if applicable}.txt`

### Version Management
- Current version: 1.0.0 (May 2025)
- Version tracking is maintained in VERSION.md
- All documents use semantic versioning where applicable

## Key Context for Modifications

When modifying documents in this repository:

1. **Legal Precision Required**: All documents have legal implications for defense contracting and intellectual property. Maintain exact terminology, especially regarding:
   - Government Purpose Rights (GPR)
   - DFARS references
   - Classification markings
   - Export control language

2. **Document Interdependencies**: Many documents reference each other. Key relationships:
   - All licenses reference the ICD Steering Body Charter for governance
   - Templates must align with their corresponding license frameworks
   - Metadata schemas impact all technical documents

3. **Compliance Framework**: Documents must maintain compatibility with:
   - DFARS 252.227 series regulations
   - 10 U.S.C. § 3458 (formerly § 2320)
   - Export control regulations (ITAR/EAR)
   - Classification guidelines

## Communication Standards

When working in this repository:
- Never use emojis in any documents, commits, or communications
- Maintain professional, concise, and clean text at all times
- Use precise technical and legal language appropriate for defense contracting
- Avoid colloquialisms or informal language

## Common Tasks

### Adding New Documents
Place new documents in the appropriate directory (licenses/, templates/, governance/, technical/, or operational/) following the naming convention. Update README.md to include the new document in the appropriate section.

### Updating Existing Documents
Preserve version history in the document header. Consider whether changes require incrementing the version number in the filename.

### Creating New Templates
Base new templates on existing formats, maintaining consistent sections for metadata, requirements, and compliance tracking.