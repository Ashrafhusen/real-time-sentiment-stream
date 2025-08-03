# real-time-sentiment-stream
A production-grade real-time data pipeline for ingesting customer reviews, performing sentiment analysis using Hugging Face models, and visualizing enriched results using Elasticsearch + Kibana.

**Components:**
- **Kafka**: Ingests raw customer reviews.
- **Spark Structured Streaming**: Reads from Kafka, performs sentiment analysis using `distilbert-base-uncased-finetuned-sst-2`.
- **MongoDB Atlas**: Stores enriched review documents.
- **Kafka Connect**: Transfers data from MongoDB to Elasticsearch.
- **Elasticsearch + Kibana**: Enables real-time search, dashboards, and geo-mapping.
- **Elasticsearch Enrich Pipeline**: Joins business metadata into reviews.

---

## 📦 Tech Stack

| Layer        | Technology                               |
|--------------|-------------------------------------------|
| Ingestion    | Kafka (Confluent)                         |
| Processing   | PySpark (Structured Streaming)            |
| ML Enrichment| Hugging Face Transformers (DistilBERT)    |
| Storage      | MongoDB Atlas, Elasticsearch              |
| Visualization| Kibana                                    |

---

## 🧪 Key Features

- Real-time ingestion and processing of review data.
- Sentiment classification using a pretrained BERT model.
- Elastic ingest pipeline enriches reviews with business metadata.
- Kibana dashboards visualize trends, sentiment, and locations.

**Components:**
- **Kafka**: Ingests raw customer reviews.
- **Spark Structured Streaming**: Reads from Kafka, performs sentiment analysis using `distilbert-base-uncased-finetuned-sst-2`.
- **MongoDB Atlas**: Stores enriched review documents.
- **Kafka Connect**: Transfers data from MongoDB to Elasticsearch.
- **Elasticsearch + Kibana**: Enables real-time search, dashboards, and geo-mapping.
- **Elasticsearch Enrich Pipeline**: Joins business metadata into reviews.

---

## 📦 Tech Stack

| Layer        | Technology                               |
|--------------|-------------------------------------------|
| Ingestion    | Kafka (Confluent)                         |
| Processing   | PySpark (Structured Streaming)            |
| ML Enrichment| Hugging Face Transformers (DistilBERT)    |
| Storage      | MongoDB Atlas, Elasticsearch              |
| Visualization| Kibana                                    |

---

## 🧪 Key Features

- Real-time ingestion and processing of review data.
- Sentiment classification using a pretrained BERT model.

- Elastic ingest pipeline enriches reviews with business metadata.'


