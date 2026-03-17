03_Data_Design
Thiết kế dữ liệu / Data design

Mục tiêu: đảm bảo RAG có dữ liệu sạch, có metadata/ACL chuẩn, có vòng đời dữ liệu rõ.
Nội dung nên có:
- Data source inventory
- Parsing/chunking strategy
- Metadata schema (doc_id, chunk_id, acl, updated_at…)
- Embedding/index versioning
- Sync & delete propagation design

Recommended files in this folder:
- 00_Data_Sources_Inventory.md
- 01_Parsing_and_Normalization.md
- 02_Chunking_Strategy.md
- 03_Metadata_Schema.md
- 04_Index_and_Embedding_Versioning.md
- 05_Sync_and_Delete_Propagation.md
