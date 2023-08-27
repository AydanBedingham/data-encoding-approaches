# One-Hot Encoding with SciKitLearn
One-Hot Encoding is a technique used to transform categorical data into numeric values understandable by machine learning algorithms.

Because the One-Hot Encoding technique converts categories into seperate columns with binary values used to indicate applicability it is best suited to nominal categorical data (categories that do not have a natural rank order) eg. the states of Australia Vicotria, Tasmania & Queensland.

Attempting to use One-Hot Encoding on ordinal categorical data (categories that have a natural rank order) can lead to machine learning algorithms failing to identify the rank order relationship eg. for T-Shirt sizes: Small is less than Medium which is less than Large so they could be label encoded as 0, 1 & 2 respectively.

The following example uses a SciKitLearn OneHotEncoder to encode a dataset containing Australian States.