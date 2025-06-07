# TFGJRR – Final Degree Project

Welcome to the repository for my **Final Degree Project**.

This project involves the development of a **web solution for supermarkets** that leverages **Artificial Intelligence** to recommend personalized recipes based on customer preferences, allergies, and the stock of perishable products, as well as other items the supermarket wants to promote.

## 🛠️ Technologies

**Backend – Microservices architecture:**
- **Business logic:** Spring Boot 3.5.0 with Java 21.
- **Database:** PostgreSQL for relational persistence.
- **Semantic processing:** SentenceTransformers connected via gRPC to Spring Boot for text vector generation.
- **Advanced search:** Elasticsearch for hybrid (vector + BM25) search.
- **Image management:** imgproxy for dynamic, optimized image serving.
- **Containerization:** Docker to deploy and connect all services.

**Frontend:**
- **Development library:** React 19.
- **Framework:** Next.js 15.2.1.
- **Styling:** Tailwind CSS v4.0.
- **UI Components:** ShadCN UI for a modern design system.

**Methodology:**
- **Personal Scrum with Jira:** 3 sprints of 3 weeks for the MVP + 1 sprint for improvements.

**Artificial Intelligence applied:**
- **Query processing and recommendation generation:** LLM integrated with LangChain.
- **Similarity search:** Embeddings model to generate text vectors.

## 🌱 Purpose

This project aims to combine technology and sustainability by optimizing the use of available products and reducing food waste.
