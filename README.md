# KeepScore: A C++ API to keep track of scores in arcade games. 
# API
|Method|Parameters|Usage|
|:---:|:---|:--|
|Score|size_t size, const char* f|Constructor for the class. size_t is number of entries to keep, and f is the filename to read/store|
|std::pair<int, std::string> getPair|size_t place|returns the pair stored at given index|
|void changeScore|size_t place, std::string<int, std::string> p|Changes the value stored at a certain index|
|void storeVector|void|write information from vector to given file|
|void readVector|void|read information from file and store to vector|
|int rankScore|int score|returns rank of given score|
|void putScore|int score, std::string name, size_t place|inserts score in index|
