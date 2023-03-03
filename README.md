# automin-2023-data
AutoMin 2023 Training and Test Data

This repo contains:
- Task A test data source side:
  - test2023-cs and test2023-en directories
  - Inside are meeting\_<lang>\_test2023\_<number> directories with one transcript each
- Task D test data source side:
  - test2023-cs and test2023-en directories
  - Inside are meeting\_<lang>\_test\_<number> and meeting\_<lang>\_test2\_<number> directories
    - transcript_MAN<number?>_annot<number>.txt - transcript file
    - minutes\_GENER\_annot<number>.txt - human reference minutes
    - minutes\_<lang>\_test_<number>\_TEAM\_<team\_number>.txt or minutes\_<lang>\_test2_<number>\_TEAM\_<team\_number>.txt - submissions to evaluate
- Europarlmin test1 data source side:
  - test1 directory
  - Inside are directories labeled by date of the session in yyyy-mm-dd format
    - ep-yyyy-mm-dd-ch\<chapter_no\>-\<part_no\>.txt - transcript file

For training data see [ELITR Minuting Corpus](https://ufal.mff.cuni.cz/elitr-minuting-corpus) and [Europarlmin](https://github.com/ufal/europarlmin).
There you will also find a detailed description of the data format.
