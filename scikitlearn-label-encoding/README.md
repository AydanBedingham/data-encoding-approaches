# Label Encoding with SciKitLearn
Label Encoding is a technique used to transform categorical data into numeric values understandable by machine learning algorithm.

Because the Label Encoding technique converts categories into ascending numeric values it is best suited to ordinal categorical data (categories that have a natural rank order) eg. for T-Shirt sizes: Small is less than Medium which is less than Large so they could be label encoded as 0, 1 & 2 respectively.

Attempting to use Label Encoding on nominal categorical data (categories that do not have a natural rank order) can lead to machine learning algorithm incorrectly inferring a natural rank order when one does not exist eg. the states of Australia Vicotria, Tasmania & Queensland do not have a natural rank order. In these cases alternate encoding approaches such as One Hot Encoding is preferred.

The following example uses a SciKitLearn Label Encoder to encode a dataset containing T-Shirt Sizes.