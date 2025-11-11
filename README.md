# Summary

The Turkish-TueCL treebank is part of a parallel Universal Dependencies corpus containing 148 sentences across four Turkic languages (Turkish, Azerbaijani, Kyrgyz, and Uzbek), designed to facilitate cross-linguistic research on these related languages.

# Introduction

The Turkish-TueCL treebank consists of 148 carefully selected sentences (904 tokens) compiled from multiple sources, including the Cairo corpus (20 sentences), the UDTW23 corpus (20 sentences), and 97 additional examples illustrating specific grammatical constructions of interest. It serves as the source treebank for a parallel corpus spanning four Turkic languages from distinct branches of the family: Turkish and Azerbaijani (Oghuz), Kyrgyz (Kipchak), and Uzbek (Karluk).

The treebank includes various syntactic phenomena relevant to Turkic languages, such as pro-drop constructions, auxiliary chains, postverbal structures, and non-canonical word orders. Each sentence has been manually annotated following UD guidelines, with particular attention to morphosyntactic features that highlight both shared typological characteristics and language-specific traits. English translations are provided as metadata to support comparative research.

This resource is significant as it represents the first fully aligned parallel UD treebanks for these Turkic languages, enabling systematic cross-linguistic comparisons previously hindered by the lack of parallel resources. The treebank supports research in comparative Turkic syntax, cross-lingual parsing, and language education.

## References

Please, cite the following paper if you use Turkish-TueCL UD treebank:

<pre>
@inproceedings{akhundjanova-etal-2025-parallel,
    title = "Parallel {U}niversal {D}ependencies Treebanks for {T}urkic Languages",
    author = "Akhundjanova, Arofat  and
      Akkurt, Furkan  and
      Chontaeva, Bermet  and
      Eslami, Soudabeh  and
      Coltekin, Cagri",
    editor = {Bouma, Gosse  and
      {\c{C}}{\"o}ltekin, {\c{C}}a{\u{g}}r{\i}},
    booktitle = "Proceedings of the Eighth Workshop on Universal Dependencies (UDW, SyntaxFest 2025)",
    month = aug,
    year = "2025",
    address = "Ljubljana, Slovenia",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2025.udw-1.14/",
    pages = "129--136",
    ISBN = "979-8-89176-292-3",
    abstract = "We introduce the first fully aligned and manually annotated parallel Universal Dependencies (UD) treebanks for four Turkic languages: Azerbaijani, Kyrgyz, Turkish, and Uzbek. These resources currently consist of 148 strategically selected sentences that illustrate typologically significant morphosyntactic phenomena across these related yet distinct languages. These parallel treebanks enable systematic comparative studies of Turkic syntax and may be instrumental in cross-lingual NLP applications. All treebanks are available as part of UD v2.16."
}
</pre>

# Acknowledgments

This work was supported by COST Action CA21167 - Universality, diversity and idiosyncrasy in language technology (UniDive). We thank the Turkic UD working group for fruitful discussions of linguistic issues and annotation approaches.

# Changelog

* 2025-09-04 v2.16
  * add reference paper
  * add parallel corpus information to machine-readable metadata
  * add parallel data support with parallel_id metadata for cross-lingual sentence matching
* 2025-05-15 v2.16
  * Initial release in Universal Dependencies.

<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.16
License: CC BY-SA 4.0
Includes text: yes
Parallel: cairo tuecl
Genre: grammar-examples
Lemmas: manual native
UPOS: manual native
XPOS: not available
Features: manual native
Relations: manual native
Contributors: Akkurt, Furkan; Çöltekin, Çağrı
Contributing: here
Contact: furkanakkurt7242@icloud.com
===============================================================================
</pre>
