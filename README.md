<h1>Detección de transacciones fraudulentas con Machine Learning</h1>


<h3>Este notebook toma un dataset libre denominado creditcard.csv el cual contiene diferentes transacciones financieras, pero debido a confidencialidad de los datos, el dataset no provee los datos sensibles de usuarios ni background de los datos, así también, las variables que se tomarán como input, pasaron por un proceso de transformación PCA, por lo que las variables más importantes están contenidas dentro de V1, V2... hasta V28. Tomar en cuenta que el dataset incluye variables no transformadas como "Time" y Amount", donde "Time" contiene los segundos entre transacciones y la primera transacción dada en el dataset y "Amount" brinda el monto de la transacción. La variable "Class" toma los valores: 1 (Fraude) o 0 (No Fraude)</h3>

<p>Link para descargar el dataset: https://huggingface.co/datasets/eveval97/transacciones_credit_card/resolve/main/transacciones_credit_card.csv</p>
