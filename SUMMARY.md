#summary
* [01_Intro](010_Intro/05_What_is_it.asciidoc)
  * [Installing_ES](010_Intro/10_Installing_ES.asciidoc)
  * [API](010_Intro/15_API.asciidoc)
  * [Document](010_Intro/20_Document.asciidoc)
  * [Tutorial_Indexing](010_Intro/25_Tutorial_Indexing.asciidoc)
  * [Tutorial_Search](010_Intro/30_Tutorial_Search.asciidoc)
  * [Tutorial_Aggregations](010_Intro/35_Tutorial_Aggregations.asciidoc)
  * [Tutorial_Conclusion](010_Intro/40_Tutorial_Conclusion.asciidoc)
  * [Distributed](010_Intro/45_Distributed.asciidoc)
  * [Conclusion](010_Intro/50_Conclusion.asciidoc)
* [02_Distributed_Cluster](020_Distributed_Cluster/00_Intro.asciidoc)
  * [Empty_cluster](020_Distributed_Cluster/05_Empty_cluster.asciidoc)
  * [Cluster_health](020_Distributed_Cluster/10_Cluster_health.asciidoc)
  * [Add_an_index](020_Distributed_Cluster/15_Add_an_index.asciidoc)
  * [Add_failover](020_Distributed_Cluster/20_Add_failover.asciidoc)
  * [Scale_horizontally](020_Distributed_Cluster/25_Scale_horizontally.asciidoc)
  * [Scale_more](020_Distributed_Cluster/30_Scale_more.asciidoc)
  * [Coping_with_failure](020_Distributed_Cluster/35_Coping_with_failure.asciidoc)
* [03_Data](030_Data/00_Intro.asciidoc)
  * [Document](030_Data/05_Document.asciidoc)
  * [Index](030_Data/10_Index.asciidoc)
  * [Get](030_Data/15_Get.asciidoc)
  * [Exists](030_Data/20_Exists.asciidoc)
  * [Update](030_Data/25_Update.asciidoc)
  * [Create](030_Data/30_Create.asciidoc)
  * [Delete](030_Data/35_Delete.asciidoc)
  * [Version_control](030_Data/40_Version_control.asciidoc)
  * [Partial_update](030_Data/45_Partial_update.asciidoc)
  * [Mget](030_Data/50_Mget.asciidoc)
  * [Bulk](030_Data/55_Bulk.asciidoc)
* [04_Distributed_CRUD](040_Distributed_CRUD/00_Intro.asciidoc)
  * [Routing](040_Distributed_CRUD/05_Routing.asciidoc)
  * [Shard_interaction](040_Distributed_CRUD/10_Shard_interaction.asciidoc)
  * [Create_index](040_Distributed_CRUD/15_Create_index_delete.asciidoc)
  * [Retrieving](040_Distributed_CRUD/20_Retrieving.asciidoc)
  * [Partial_updates](040_Distributed_CRUD/25_Partial_updates.asciidoc)
  * [Bulk_requests](040_Distributed_CRUD/30_Bulk_requests.asciidoc)
  * [Bulk_format](040_Distributed_CRUD/35_Bulk_format.asciidoc)
* [05_Search](050_Search/00_Intro.asciidoc)
  * [Empty_search](050_Search/05_Empty_search.asciidoc)
  * [Multi_index_multi_type](050_Search/10_Multi_index_multi_type.asciidoc)
  * [Pagination](050_Search/15_Pagination.asciidoc)
  * [Query_string](050_Search/20_Query_string.asciidoc)
* [06_Mapping_Analysis]
  * [Data_type_differences](052_Mapping_Analysis/25_Data_type_differences.asciidoc)
  * [Exact_vs_full_text](052_Mapping_Analysis/30_Exact_vs_full_text.asciidoc)
  * [Inverted_index](052_Mapping_Analysis/35_Inverted_index.asciidoc)
  * [Analysis](052_Mapping_Analysis/40_Analysis.asciidoc)
  * [Mapping](052_Mapping_Analysis/45_Mapping.asciidoc)
  * [Complex_datatypes](052_Mapping_Analysis/50_Complex_datatypes.asciidoc)
* [07_Query_DSL]
  * [Request_body_search](054_Query_DSL/55_Request_body_search.asciidoc)
  * [Query_DSL](054_Query_DSL/60_Query_DSL.asciidoc)
  * [Queries_vs_filters](054_Query_DSL/65_Queries_vs_filters.asciidoc)
  * [Important_clauses](054_Query_DSL/70_Important_clauses.asciidoc)
  * [Combining_queries_together](054_Query_DSL/75_Combining_queries_together.asciidoc)
  * [Validating_queries](054_Query_DSL/80_Validating_queries.asciidoc)
* [08_Sorting]
 * [Sorting](056_Sorting/85_Sorting.asciidoc)
 * [String_sorting](056_Sorting/88_String_sorting.asciidoc)
 * [What_is_relevance](056_Sorting/90_What_is_relevance.asciidoc)
 * [Docvalues](056_Sorting/95_Docvalues.asciidoc)
* [09_Distributed_Search](060_Distributed_Search/00_Intro.asciidoc)
 * [Query_phase](060_Distributed_Search/05_Query_phase.asciidoc)
 * [Fetch_phase](060_Distributed_Search/10_Fetch_phase.asciidoc)
 * [Search_options](060_Distributed_Search/15_Search_options.asciidoc)
 * [Scroll](060_Distributed_Search/20_Scroll.asciidoc)
* [10_Index_Mgmt]
 * [Create_Delete](070_Index_Mgmt/05_Create_Delete.asciidoc)
 * [Settings](070_Index_Mgmt/10_Settings.asciidoc)
 * [Configure_Analyzer](070_Index_Mgmt/15_Configure_Analyzer.asciidoc)
 * [Custom_Analyzers](070_Index_Mgmt/20_Custom_Analyzers.asciidoc)
 * [Mappings](070_Index_Mgmt/25_Mappings.asciidoc)
 * [Root_Object](070_Index_Mgmt/30_Root_Object.asciidoc)
 * [Dynamic_Mapping](070_Index_Mgmt/35_Dynamic_Mapping.asciidoc)
 * [Custom_Dynamic_Mapping](070_Index_Mgmt/40_Custom_Dynamic_Mapping.asciidoc)
 * [Default_Mapping](070_Index_Mgmt/45_Default_Mapping.asciidoc)
 * [Reindexing](070_Index_Mgmt/50_Reindexing.asciidoc)
 * [Aliases](070_Index_Mgmt/55_Aliases.asciidoc)
* [11_Inside_a_shard](075_Inside_a_shard/10_Intro.asciidoc)
 * [Making_text_searchable](075_Inside_a_shard/20_Making_text_searchable.asciidoc)
 * [Dynamic_indices](075_Inside_a_shard/30_Dynamic_indices.asciidoc)
 * [Near_real_time](075_Inside_a_shard/40_Near_real_time.asciidoc)
 * [Persistent_changes](075_Inside_a_shard/50_Persistent_changes.asciidoc)
 * [Segment_merging](075_Inside_a_shard/60_Segment_merging.asciidoc)
* [12_Structured_Search]
 * [structuredsearch](080_Structured_Search/00_structuredsearch.asciidoc)
 * [term](080_Structured_Search/05_term.asciidoc)
 * [compoundfilters](080_Structured_Search/10_compoundfilters.asciidoc)
 * [terms](080_Structured_Search/15_terms.asciidoc)
 * [contains](080_Structured_Search/20_contains.asciidoc)
 * [ranges](080_Structured_Search/25_ranges.asciidoc)
 * [existsmissing](080_Structured_Search/30_existsmissing.asciidoc)
 * [bitsets](080_Structured_Search/40_bitsets.asciidoc)
* [13_Full_Text_Search](100_Full_Text_Search/00_Intro.asciidoc)
 * [Match_query](100_Full_Text_Search/05_Match_query.asciidoc)
 * [Multi_word_queries](100_Full_Text_Search/10_Multi_word_queries.asciidoc)
 * [Combining_queries](100_Full_Text_Search/15_Combining_queries.asciidoc)
 * [How_match_uses_bool](100_Full_Text_Search/20_How_match_uses_bool.asciidoc)
 * [Boosting_clauses](100_Full_Text_Search/25_Boosting_clauses.asciidoc)
 * [Controlling_analysis](100_Full_Text_Search/30_Controlling_analysis.asciidoc)
 * [Relevance_is_broken](100_Full_Text_Search/35_Relevance_is_broken.asciidoc)
* [14_Multi_Field_Search](110_Multi_Field_Search/00_Intro.asciidoc)
 * [Multiple_query_strings](110_Multi_Field_Search/05_Multiple_query_strings.asciidoc)
 * [Single_query_string](110_Multi_Field_Search/10_Single_query_string.asciidoc)
 * [Best_field](110_Multi_Field_Search/15_Best_field.asciidoc)
 * [Tuning_best_field_queries](110_Multi_Field_Search/20_Tuning_best_field_queries.asciidoc)
 * [Multi_match_query](110_Multi_Field_Search/25_Multi_match_query.asciidoc)
 * [Most_fields](110_Multi_Field_Search/30_Most_fields.asciidoc)
 * [Entity_search](110_Multi_Field_Search/35_Entity_search.asciidoc)
 * [Field_centric](110_Multi_Field_Search/40_Field_centric.asciidoc)
 * [Custom_all](110_Multi_Field_Search/45_Custom_all.asciidoc)
 * [Cross_field](110_Multi_Field_Search/50_Cross_field.asciidoc)
 * [Not_analyzed](110_Multi_Field_Search/55_Not_analyzed.asciidoc)
* [15_Proximity_Matching](120_Proximity_Matching/00_Intro.asciidoc)
 * [Phrase_matching](120_Proximity_Matching/05_Phrase_matching.asciidoc)
 * [Slop](120_Proximity_Matching/10_Slop.asciidoc)
 * [Multi_value_fields](120_Proximity_Matching/15_Multi_value_fields.asciidoc)
 * [Scoring](120_Proximity_Matching/20_Scoring.asciidoc)
 * [Relevance](120_Proximity_Matching/25_Relevance.asciidoc)
 * [Performance](120_Proximity_Matching/30_Performance.asciidoc)
 * [Shingles](120_Proximity_Matching/35_Shingles.asciidoc)
* [16_Partial_Matching](130_Partial_Matching/00_Intro.asciidoc)
 * [Postcodes](130_Partial_Matching/05_Postcodes.asciidoc)
 * [Prefix_query](130_Partial_Matching/10_Prefix_query.asciidoc)
 * [WildcardRegexp](130_Partial_Matching/15_WildcardRegexp.asciidoc)
 * [Match_phrase_prefix](130_Partial_Matching/20_Match_phrase_prefix.asciidoc)
 * [Index_time](130_Partial_Matching/25_Index_time.asciidoc)
 * [Ngram_intro](130_Partial_Matching/30_Ngram_intro.asciidoc)
 * [Search_as_you_type](130_Partial_Matching/35_Search_as_you_type.asciidoc)
 * [Compound_words](130_Partial_Matching/40_Compound_words.asciidoc)
* [17_Relevance](170_Relevance/05_Intro.asciidoc)
 * [Scoring_theory](170_Relevance/10_Scoring_theory.asciidoc)
 * [Practical_scoring](170_Relevance/15_Practical_scoring.asciidoc)
 * [Query_time_boosting](170_Relevance/20_Query_time_boosting.asciidoc)
 * [Query_scoring](170_Relevance/25_Query_scoring.asciidoc)
 * [Not_quite_not](170_Relevance/30_Not_quite_not.asciidoc)
 * [Ignoring_TFIDF](170_Relevance/35_Ignoring_TFIDF.asciidoc)
 * [Function_score_query](170_Relevance/40_Function_score_query.asciidoc)
 * [Popularity](170_Relevance/45_Popularity.asciidoc)
 * [Boosting_filtered_subsets](170_Relevance/50_Boosting_filtered_subsets.asciidoc)
 * [Random_scoring](170_Relevance/55_Random_scoring.asciidoc)
 * [Decay_functions](170_Relevance/60_Decay_functions.asciidoc)
 * [Script_score](170_Relevance/65_Script_score.asciidoc)
 * [Pluggable_similarities](170_Relevance/70_Pluggable_similarities.asciidoc)
 * [Changing_similarities](170_Relevance/75_Changing_similarities.asciidoc)
 * [Conclusion](170_Relevance/80_Conclusion.asciidoc)
* [18_Language_intro](200_Language_intro/00_Intro.asciidoc)
 * [Using](200_Language_intro/10_Using.asciidoc)
 * [Configuring](200_Language_intro/20_Configuring.asciidoc)
 * [Language_pitfalls](200_Language_intro/30_Language_pitfalls.asciidoc)
 * [One_language_per_doc](200_Language_intro/40_One_language_per_doc.asciidoc)
 * [One_language_per_field](200_Language_intro/50_One_language_per_field.asciidoc)
 * [Mixed_language_fields](200_Language_intro/60_Mixed_language_fields.asciidoc)
* [19_Identifying_words](210_Identifying_words/00_Intro.asciidoc)
 * [Standard_analyzer](210_Identifying_words/10_Standard_analyzer.asciidoc)
 * [Standard_tokenizer](210_Identifying_words/20_Standard_tokenizer.asciidoc)
 * [ICU_plugin](210_Identifying_words/30_ICU_plugin.asciidoc)
 * [ICU_tokenizer](210_Identifying_words/40_ICU_tokenizer.asciidoc)
 * [Tidying_text](210_Identifying_words/50_Tidying_text.asciidoc)
* [20_Token_normalization](220_Token_normalization/00_Intro.asciidoc)
 * [Lowercasing](220_Token_normalization/10_Lowercasing.asciidoc)
 * [Removing_diacritics](220_Token_normalization/20_Removing_diacritics.asciidoc)
 * [Unicode_world](220_Token_normalization/30_Unicode_world.asciidoc)
 * [Case_folding](220_Token_normalization/40_Case_folding.asciidoc)
 * [Character_folding](220_Token_normalization/50_Character_folding.asciidoc)
 * [Sorting_and_collations](220_Token_normalization/60_Sorting_and_collations.asciidoc)
* [21_Stemming](230_Stemming/00_Intro.asciidoc)
 * [Algorithmic_stemmers](230_Stemming/10_Algorithmic_stemmers.asciidoc)
 * [Dictionary_stemmers](230_Stemming/20_Dictionary_stemmers.asciidoc)
 * [Hunspell_stemmer](230_Stemming/30_Hunspell_stemmer.asciidoc)
 * [Choosing_a_stemmer](230_Stemming/40_Choosing_a_stemmer.asciidoc)
 * [Controlling_stemming](230_Stemming/50_Controlling_stemming.asciidoc)
 * [Stemming_in_situ](230_Stemming/60_Stemming_in_situ.asciidoc)
* [22_Stopwords](240_Stopwords/10_Intro.asciidoc)
 * [Using_stopwords](240_Stopwords/20_Using_stopwords.asciidoc)
 * [Stopwords_and_performance](240_Stopwords/30_Stopwords_and_performance.asciidoc)
 * [Divide_and_conquer](240_Stopwords/40_Divide_and_conquer.asciidoc)
 * [Phrase_queries](240_Stopwords/50_Phrase_queries.asciidoc)
 * [Common_grams](240_Stopwords/60_Common_grams.asciidoc)
 * [Relevance](240_Stopwords/70_Relevance.asciidoc)
* [23_Synonyms](260_Synonyms/10_Intro.asciidoc)
 * [Using_synonyms](260_Synonyms/20_Using_synonyms.asciidoc)
 * [Synonym_formats](260_Synonyms/30_Synonym_formats.asciidoc)
 * [Expand_contract](260_Synonyms/40_Expand_contract.asciidoc)
 * [Analysis_chain](260_Synonyms/50_Analysis_chain.asciidoc)
 * [Multi_word_synonyms](260_Synonyms/60_Multi_word_synonyms.asciidoc)
 * [Symbol_synonyms](260_Synonyms/70_Symbol_synonyms.asciidoc)
* [24_Fuzzy_matching](270_Fuzzy_matching/10_Intro.asciidoc)
 * [Fuzziness](270_Fuzzy_matching/20_Fuzziness.asciidoc)
 * [Fuzzy_query](270_Fuzzy_matching/30_Fuzzy_query.asciidoc)
 * [Fuzzy_match_query](270_Fuzzy_matching/40_Fuzzy_match_query.asciidoc)
 * [Scoring_fuzziness](270_Fuzzy_matching/50_Scoring_fuzziness.asciidoc)
 * [Phonetic_matching](270_Fuzzy_matching/60_Phonetic_matching.asciidoc)
