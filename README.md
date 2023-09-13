# AutoMin 2023 Data

This repo contains all test data (source and target) in the directory **test_data**:
- Task A test data source and target side:
  - ``test2023-cs`` and ``test2023-en`` directories
  - Inside are ``meeting_<lang>_test2023_<number>`` directories with one transcript and reference minutes each
- Task D test data source side:
  - ``test2023-cs`` and ``test2023-en`` directories
  - Inside are ``meeting_<lang>_test_<number>`` and ``meeting_<lang>_test2_<number>`` directories
    - ``transcript_MAN<number?>_annot<number>.txt``
      - transcript file
    - ``minutes_GENER_annot<number>.txt``
      - human reference minutes
    - ``minutes_<lang>_test_<number>_TEAM_<team_number>.txt`` or ``minutes_<lang>_test2_<number>_TEAM_<team_number>.txt``
      - submissions to evaluate
- Europarlmin test1 data source and target side:
  - ``test1`` directory
  - Inside are directories labeled by date of the session in ``yyyy-mm-dd`` format
    - ``ep-yyyy-mm-dd-ch<chapter_no>-<part_no>.txt`` - transcript file
    - ``min-yyyy-mm-dd-ch<chapter_no>-<part_no>.txt`` - minutes file

In the directory **submissions-and-evaluation** you will find participant submissions and manual alignments and evaluation scores.

For **training data** see [ELITR Minuting Corpus](https://ufal.mff.cuni.cz/elitr-minuting-corpus) and [Europarlmin](https://github.com/ufal/europarlmin).
There you will also find a detailed description of the data format.
