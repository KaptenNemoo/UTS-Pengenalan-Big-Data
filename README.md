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

<br>2. Download package dan ekstrak

<br>3.  Menambahkan repository cassandra ke `etc/apt/sources.list.d/cassandra/sources.list`<br>
`echo "deb https://downloads.apache.org/cassandra/debian 311x main" | sudo tee -a /etc/apt/sources.list.d/cassandra.sources.list`

<br>4. menambahkan key repository

<br>5. Menambahkan public key

<br>6. Install Cassandra

<br>7.  Selesai
 untuk menjalankan cassandra `sudo service cassandra start` untuk berhenti `sudo service cassandra stop`. 

 
</div>


<div> 
CRUD CASSANDRA<br>
1. menjalankan cql

2. membuat keyspace











3. menggunakan keyspace akademik dan membuat table mahasiswa (create)









4. menginput data/insert into table mahasiswa (create)

5. membaca isi table (read)

6. mengupdate data (update)








7. menghapus data(delete)


</div>

