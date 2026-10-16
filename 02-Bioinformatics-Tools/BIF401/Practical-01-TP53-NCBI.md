# 🧬 Practical 01: Exploring the TP53 Gene Using NCBI

- **Course:** BIF401 — Bioinformatics I
- **Project:** Bioinformatics-Journey
- **Topic:** NCBI Nucleotide Database Exploration

---

## 1. Overview

This practical introduces the use of the National Center for Biotechnology Information (NCBI) database to explore biological sequence records. The human TP53 gene was used as an example to understand nucleotide records, accession numbers, sequence length, biological annotations, and sequence formats.

## 2. Objectives

- To learn how to search for TP53 in the NCBI Nucleotide database.
- To identify important information in a nucleotide sequence record.
- To understand the purpose of accession numbers and version numbers.
- To distinguish between GenBank and FASTA formats.
- To understand sequence length and partial coding sequence annotations.

## 3. Database and Record Information

| Field | Observation / Value |
|---|---|
| Database | NCBI Nucleotide |
| Record Title | *Homo sapiens* TP53 gene, exon 5 and partial cds |
| Organism | *Homo sapiens* (Human) |
| Accession Number | `MH011443` |
| Version | `MH011443.1` |
| Sequence Length | 123 bp |
| Molecule Type | DNA |
| Record Type | Partial sequence record |

## 4. Background

TP53 is a human gene that provides instructions for producing the p53 protein. This protein plays an important role in cellular responses to DNA damage and the regulation of cell growth.

NCBI provides access to biological information, including nucleotide sequences and their associated annotations. These resources help students and researchers explore genetic information.

## 5. Methodology

1. Opened the NCBI website.
2. Selected the **Nucleotide** database.
3. Entered `TP53` in the search box.
4. Examined the search results and opened a human TP53 record.
5. Reviewed the GenBank record to identify the organism, accession number, sequence length, and annotated features.
6. Opened the FASTA view to examine the nucleotide sequence in a simplified format.
7. Compared the information available in GenBank and FASTA formats.

## 6. Key Observations

### 6.1 Organism

The organism is listed as *Homo sapiens*, which refers to humans.

### 6.2 Accession Number and Version

- **Accession Number (`MH011443`):** An identifier used to locate and retrieve a specific sequence record.
- **Version (`MH011443.1`):** Identifies a particular version of the sequence record. The version number changes when the nucleotide sequence is updated.

### 6.3 Sequence Length

The GenBank `LOCUS` line reports a sequence length of **123 bp**, where bp stands for base pairs. This length describes the sequence represented by the particular record examined, not the entire human TP53 gene.

### 6.4 Exon and Partial CDS

The record title includes *exon 5* and *partial cds*.

- **Exon 5:** Indicates that the record relates to the fifth exon of the TP53 gene.
- **CDS (Coding Sequence):** The region of a nucleotide sequence that specifies the amino-acid sequence of a protein.
- **Partial CDS:** Indicates that only part of the coding sequence is represented in the record.

### 6.5 GenBank and FASTA Formats

- **GenBank Format:** Provides the nucleotide sequence along with detailed information, such as organism details, accession number, references, and annotated features.
- **FASTA Format:** A simple text-based format containing a header line beginning with `>` followed by the nucleotide sequence.

## 7. GenBank vs. FASTA Comparison

| Feature | GenBank Format | FASTA Format |
|---|---|---|
| Main Purpose | Detailed sequence record | Simple sequence representation |
| Biological Annotations | Included | Generally not included |
| Header | Detailed record fields | Header begins with `>` |
| Sequence Data | Included | Included |

## 8. Conclusion

This practical provided an introduction to exploring nucleotide records using NCBI. I learned how to search for a human TP53 record, identify its accession number and sequence length, and distinguish between GenBank and FASTA formats.

I also learned the importance of reading record descriptions carefully. The 123 bp length applies to the specific partial sequence examined, rather than the entire TP53 gene.

## 9. Learning Outcomes

After completing this practical, I can:

- Search for TP53 in the NCBI Nucleotide database.
- Identify basic information in a nucleotide sequence record.
- Explain accession numbers, version numbers, and sequence length.
- Distinguish between GenBank and FASTA formats.
- Explain the meaning of a partial CDS annotation.

---

**Course:** BIF401 — Bioinformatics I  
**Repository:** Bioinformatics-Journey  
**Practical:** 01 — NCBI Nucleotide Database Exploration
