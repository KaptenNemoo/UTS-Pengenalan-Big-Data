# UTS-Pengenalan-Big-Data

<h3>1. Cari dan sebutkan 3 DBMS yang bisa digunakan untuk mengelola big data</h3>
berdasarkan tipe <br>
    • key value : Riak, Redis, Couchbase, Dynamodb <br>
    • document : Apache CouchDB, ArangoDB, BaseX, Clusterpoint <br>
    • graph : Neo4J, OrientDB, Virtuoso <br>
    • kolom : Cassandra, Scylla, Apache Druid, HBase<br>
    
<div>
   <h3>2. Carilah contoh masalah big data yang bisa dikelola menggunakan salah satu DBMS tersebut, jelaskan mulai dari instalasi sampai CRUD untuk data menggunakan DBMS tersebut. Asumsikan anda akan memecahkan masalah big data yang sudah anda cari contoh tadi, jelaskan kira-kira bagaimana arsitektur dari solusi big data menggunakan DBMS tersebut, gambarkan diagramnya</h3> 
CASSANDRA <br>
INSTALASI<br>
1. cek java dan jdk apakah sudah terinstall<br>
<iframe width="420" height="315"
src="img/">
</iframe>
2. Download package dan ekstrak

3.  Menambhkan repository cassandra ke etc/apt/sources.list.d/cassandra/sources.list
echo "deb https://downloads.apache.org/cassandra/debian 311x main" | sudo tee -a /etc/apt/sources.list.d/cassandra.sources.list

4. menambahkan key repository

5. Menambahkan public key

6. Install Cassandra

7.  Selesai
 untuk menjalankan cassandra sudo service cassandra start untuk berhenti sudo service cassandra stop. 

 
</div>

