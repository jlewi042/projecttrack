# Workflow Design

ProjectTrack follows a structured workflow to process new PWS documents, compare them with past performance, and generate proposal deliverables.

## Workflow Overview

```
┌─────────────────┐     ┌─────────────────┐     ┌─────────────────┐
│  Document       │     │  Analysis &      │     │  Deliverable    │
│  Ingestion      │────▶│  Processing     │────▶│  Generation     │
└─────────────────┘     └─────────────────┘     └─────────────────┘
        │                       │                       │
        ▼                       ▼                       ▼
┌─────────────────┐     ┌─────────────────┐     ┌─────────────────┐
│  Document       │     │  Relevancy      │     │  Quality        │
│  Classification │     │  Assessment     │     │  Assurance      │
└─────────────────┘     └─────────────────┘     └─────────────────┘
```

## Detailed Workflow Stages

### 1. Document Ingestion

- **New PWS Upload**: Process new PWS documents to identify requirements and sections
- **Past Performance Repository Access**: Connect to repository of past proposals, PWS documents, and CPAR scores
- **Document Classification**: Automatically categorize uploaded documents by type
- **Document Preprocessing**: Extract text and structure from various document formats

### 2. Analysis & Processing

- **PWS Analysis**: Parse new PWS into structured sections and requirements
- **Past Performance Matching**: Compare new PWS sections with legacy PWS documents
- **Gap Analysis**: Identify areas with strong past performance alignment and flag areas with limited or no relevant past performance

### 3. Relevancy Assessment

- **Relevancy Scoring**: Apply FAR 15.305(a)(2) past-performance policy criteria
- **Evidence Compilation**: Extract relevant metrics from past performance documents
- **Teammate Identification**: For Yellow-coded areas, identify potential teammates with relevant experience

### 4. Deliverable Generation

- **PWS Crosswalk Table Creation**: Generate two-column table mapping new PWS sections to legacy PWS sections
- **Relevancy Grid Development**: Create grid with one row per reference contract
- **Story Block Generation**: Draft Challenge-Action-Result narratives for each major PWS requirement
- **Past-Performance Volume Assembly**: Structure document with mirror headings matching evaluation factors

### 5. Quality Assurance

- **Compliance Checking**: Verify adherence to 508/readability requirements
- **Gap Identification**: Generate Questions List for missing information
- **Style and Tone Review**: Ensure formal, active voice with varied sentence length

### 6. Feedback and Iteration

- **User Review Interface**: Present deliverables for user review and approval
- **Iterative Refinement**: Apply user feedback to improve deliverables
- **Lessons Learned Compilation**: After approval, generate 1-page Lessons-Learned summary

## Agent Features

### Document Processing Features

- **Intelligent Document Parsing**: Extract structured content from various document formats
- **Semantic Search and Matching**: Find relevant past performance based on semantic similarity
- **Automated Classification**: Categorize documents by type and relevance

### Analysis Features

- **Relevancy Assessment Engine**: Score past performance on multiple dimensions
- **Gap Analysis Tools**: Identify areas lacking strong past performance
- **Metric Extraction**: Identify quantitative performance metrics in past documents

### Content Generation Features

- **PWS Crosswalk Generator**: Create structured comparison tables
- **Story Block Composer**: Generate Challenge-Action-Result narratives
- **Volume Assembly Engine**: Structure documents according to Mirror Method architecture

### User Interface Features

- **Document Upload and Management**: Batch upload capabilities for document libraries
- **Interactive Deliverable Review**: In-line editing and feedback capabilities
- **Collaboration Tools**: Role-based access for proposal team members

### Quality Assurance Features

- **Compliance Checker**: Verify 508/readability requirements
- **Style and Tone Analyzer**: Ensure formal, active voice
- **Questions and Gaps Identifier**: Generate structured lists of information needs
