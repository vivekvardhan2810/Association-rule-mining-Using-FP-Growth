# Association-rule-mining-Using-FP-Growth
<p>Association rule mining is a technique in data mining that aims to discover interesting relationships, patterns, or associations among a set of items in large datasets. This method is commonly used in market basket analysis, where the goal is to identify associations between products that are frequently purchased together. Association rule mining is widely applied in various domains, including retail, healthcare, and telecommunications.</p>

<b>Explaination:</b>
<p>1) The code imports necessary libraries, including pandas for data manipulation, TransactionEncoder from mlxtend.preprocessing for converting transaction data, and functions for frequent pattern mining and association rule generation from mlxtend.</p>
<p>2) A dataset is created as a list of lists, where each inner list represents a transaction containing items (e.g., movies like 'TFIOS', '5 feet apart', etc.).</p>
<p>3) An instance of TransactionEncoder is created to convert the dataset into a binary matrix format suitable for association rule mining.</p>
