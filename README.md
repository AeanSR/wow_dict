# World of Warcraft Chinese Dictionary

This dictionary is discovered by word extraction algorithm from all zh_cn locale strings exported from database client. This is the raw output, not revised by human, so the precision and recall rate are without any guarantee.

The dict is encoded as UTF-8(with BOM), tab-delimited. Line ends with single LF(Unix style).

The first column is the word, the second column is the frequency, the third column is the coherency, the last column is the entropy.

Frequency indicates how many times this word appeared.

Coherency indicates how close are characters coupled in this word. E.g. “玫瑰” will get a high coherency because each time “玫” appears, it's always followed by “瑰”.

Entropy indicates the freedom of this word's usage, how rich are the contexts may be around the word. E.g. “费伍德” will get a low coherency because it could only be used in few contexts, mainly in “费伍德森林”.
