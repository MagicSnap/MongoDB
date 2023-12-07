### MongoDB ![Лого](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTcC_kssKzVz-xOR9BM88d12Z3Ushqlg9olUg&usqp=CAU)
MongoDB относится к **_Consistency-Partition_** системам 
так как:
* MongoDB обеспечивает strong consistency, потому что это система с одним Master узлом, и все записи идут по умолчанию в него.
*   Автоматическая смена мастера, в случае отделения его от остальных узлов.
* В случае разделения сети, система прекратит принимать записи до тех пор, пока не убедится, что может безопасно завершить их. 

[Ссылка на текст статьи](https://habr.com/ru/articles/328792/#:~:text=MongoDB%20%D0%BE%D0%B1%D0%B5%D1%81%D0%BF%D0%B5%D1%87%D0%B8%D0%B2%D0%B0%D0%B5%D1%82%20strong,%D0%B1%D0%B5%D0%B7%D0%BE%D0%BF%D0%B0%D1%81%D0%BD%D0%BE%20%D0%B7%D0%B0%D0%B2%D0%B5%D1%80%D1%88%D0%B8%D1%82%D1%8C%20%D0%B8%D1%85.)