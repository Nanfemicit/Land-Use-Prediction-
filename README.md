# Land Use Prediction Using PoI Website Contents
**Student:** Ruth Femicit Dala · Student no. 2839575  
**Supervisor:** Dr. Alex Levering · Vrije Universiteit Amsterdam  
**Status:** In progress

---

## Project summary

This research designs and evaluates a prototype pipeline that collects Points of Interest (PoI) 
website content, processes it using large language model extraction, and generates 
lifestyle-informed neighbourhood profiles for Amsterdam. It addresses both the technical 
pipeline question and the policy question: are coverage gaps in website availability 
socio-economically patterned, and what does this mean for responsible use in urban planning?

---

## Repository structure

| Notebook | Phase | Weeks | Contents |
|---|---|---|---|
| [Phase1_PoI_Collection.ipynb](./Phase1_PoI_Collection.ipynb) | Data collection | 4–7 | OSM Overpass query, scraping pipeline, raw content export |
| [Phase2_Analysis.ipynb](./Phase2_Analysis.ipynb) | Analysis | 9–12 | LLM extraction, bias analysis, lifestyle mapping |
| [Phase3_Outputs.ipynb](./Phase3_Outputs.ipynb) | Outputs | 12–16 | FAIR dataset documentation, final maps, replication guide |

Supporting outputs are in `/data/` (raw and enriched PoI datasets) and `/maps/` (choropleth outputs).

---

## Research questions

**Main question:** To what extent does the website content of Points of Interest enable 
lifestyle-informed characterisation of urban neighbourhoods beyond standard functional 
classification, given the socio-economic and ethical constraints of this data source?

**Sub-questions:** SQ1 (lifestyle indicator extraction) · SQ2 (added value over standard PoI labels) · 
SQ3 (coverage–socioeconomic correlation) · SQ4 (responsible scraping conditions)

---

## Reproducibility

All analysis runs in Google Colab. Each notebook begins with a setup cell that installs 
required packages. Data outputs follow FAIR principles (Wilkinson et al., 2016) and are 
documented using the Datasheets for Datasets framework (Gebru et al., 2021).
