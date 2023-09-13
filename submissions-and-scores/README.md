# Annotated Meetings

Here you will find all transcripts, team submissions, references and their alignments and evaluations. separated by testest.

## Files
 - Transcript files start with ``transcript``, minutes files start with ``minutes`` for ELITR sets and with ``min`` and ``ep`` respecively for EuroParl set.
 - Alignment files start with ``alignment``, evaluation files start with ``evaluation`` and in both cases are followed by plus-separated name of the transcript and minutes file they're associated with.
 - This format can easily be opened in ALIGNMEET tool for better visualization.
 - Minutes files with names containing ``annot`` are references created by human annotators.
 - Minutes files with ``gpt4`` and ``davinci-003`` in the name were generated by us using those language models.
 - All other minues files are participant submissions.
 - For EuroParl set, the manually annotated submissions are in a separate subdirectory ``annotated``.

## Format:
 - Alignment is in ``alignment+transcript_file+miutes_file`` and each line in it is tab-separated transcript line, minutes line, problem tag (indexed from 1 or None if not applicable).
 - Evaluation is in ``evaluation+transcript_file+miutes_file``and each line is Adequacy, Grammaticality, Fluency, Relevance from 1 to 5, separated by ^.
    - If scores are -1, the line has not been scored.
    - The first line is doc-level scores.
    - The ``+aggreg-hunks`` files contain aggregated hunk-based manual scores for each minute.

## Tables:
 - ``<testset>-overall-doc-level-scores.tsv`` contains aggregated doc level scores.
 - ``<testset>-overall-hunk-level-scores.tsv`` contains aggregated hunk level scores.