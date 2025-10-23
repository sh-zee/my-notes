1. Structure
	1. SQL: too many connected components with relations
	2. Document: One big object
	3. Graph: very high relations
2. Flexibility:
	1. SQL: strong schema, Schema at write validation, expensive migrations
	2. Documents: Almost no structure and data validation at read, handeling at read or lazy migrations.
3. Query:
	1. SQL: high number of queries especillay writes on the same data. With huge joins
	2. NoSQL: reads on local data, huge number of writes on small part will be slow. Access bug data records.
	3. Cypher: Focus on the readability as a relation
