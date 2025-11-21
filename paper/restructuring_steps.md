## Phase 6: Update Main Document Structure

### Step 6.1: Update Preamble
- [ ] Review and update custom commands if needed
- [ ] Ensure all new environments defined
- [ ] Add any new formatting commands
- [ ] Verify bibliography setup

**Output:** `preamble_v2.tex`

### Step 6.2: Create New Main File
- [ ] Update title and metadata
- [ ] Rewrite abstract to reflect new structure
- [ ] Update table of contents structure
- [ ] Update section \input{} statements to new files
- [ ] Ensure all 8 new stack files included
- [ ] Ensure all appendices included

**Output:** `main_v2.tex`

### Step 6.3: Update Bibliography
- [ ] Add any new citations needed
- [ ] Remove unused citations
- [ ] Verify all citations used in new text

**Output:** `bibliography_v2.bib`

---

## Phase 7: Quality Assurance

### Step 7.1: Consistency Check
- [ ] Verify all 35 abstract mechanisms use identical template structure
- [ ] Check consistent use of terminology throughout
- [ ] Verify depth notation consistent (E/M/L/F)
- [ ] Check implementation descriptions follow "what then how" pattern
- [ ] Verify all cross-references work

### Step 7.2: Completeness Check
- [ ] Confirm all 35 mechanisms documented
- [ ] Verify each mechanism has all required sections
- [ ] Check that no content from original was lost unintentionally
- [ ] Ensure all important circuits still covered
- [ ] Verify all key examples preserved

### Step 7.3: Technical Review
- [ ] Compile LaTeX document
- [ ] Check for compilation errors
- [ ] Verify all citations render correctly
- [ ] Check all cross-references resolve
- [ ] Review PDF formatting and layout

### Step 7.4: Content Review
- [ ] Read through entire document for flow
- [ ] Check that abstract mechanisms are well-defined
- [ ] Verify implementation details are accurate
- [ ] Check examples are clear and correct
- [ ] Ensure ablation effects are realistic

### Step 7.5: Scientific Accuracy Review
- [ ] Verify all empirical claims have citations
- [ ] Check that status labels are accurate (well-documented/observed/proposed)
- [ ] Ensure no overclaiming of mechanism understanding
- [ ] Verify depth ranges match literature where known

---

## Phase 8: Finalization

### Step 8.1: Create Comparison Document
- [ ] Document showing old vs. new structure
- [ ] Highlighting key improvements
- [ ] Explaining rationale for major changes

**Output:** `restructuring_summary.md`

### Step 8.2: Final Polish
- [ ] Proofread entire document
- [ ] Fix typos and grammar
- [ ] Improve unclear passages
- [ ] Ensure consistent tone
- [ ] Check formatting consistency

### Step 8.3: Generate Deliverables
- [ ] Compile final PDF
- [ ] Create all output files in /mnt/user-data/outputs/
- [ ] Generate supplementary materials (mapping tables, etc.)

**Outputs:**
- `mechanism_taxonomy_v2.pdf` - Main document
- `mapping_old_to_new.csv` - Conversion table
- `mechanism_summary_table.pdf` - Quick reference

---

## Estimated Timeline

**Phase 1 (Preparation):** 1-2 days
**Phase 2 (Extraction):** 2-3 days  
**Phase 3 (Writing Stacks):** 5-7 days (most intensive)
**Phase 4 (Supporting Sections):** 2-3 days
**Phase 5 (Appendices):** 2-3 days
**Phase 6 (Main Structure):** 1 day
**Phase 7 (QA):** 2-3 days
**Phase 8 (Finalization):** 1 day

**Total:** 16-23 days of focused work

---

## Key Principles Throughout

1. **Preserve empirical grounding** - Don't lose citations or evidence
2. **Maintain clarity** - Abstract doesn't mean vague
3. **Separate what from how** - Keep mechanism vs. implementation clean
4. **Enable cross-model comparison** - Stay architecture-agnostic where possible
5. **Support practitioners** - Make taxonomy actionable for researchers
6. **Document uncertainties** - Clear about what's well-known vs. proposed

---

## Success Criteria

- [ ] Document compiles without errors
- [ ] All 35 abstract mechanisms documented with complete templates
- [ ] All 8 stacks have clear, coherent organization
- [ ] Infrastructure properly relegated to appendix
- [ ] Cross-references work correctly
- [ ] Document length ~50 pages
- [ ] Improved clarity and reduced redundancy vs. original
- [ ] Maintains scientific rigor and empirical grounding
- [ ] Provides clear mapping from old to new taxonomy
