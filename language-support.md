---

copyright:
  years: 2019, 2020
lastupdated: "2020-06-19"

subcollection: watson-knowledge-studio-data

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}
{:tip: .tip}
{:pre: .pre}
{:codeblock: .codeblock}
{:screen: .screen}
{:javascript: .ph data-hd-programlang='javascript'}
{:java: .ph data-hd-programlang='java'}
{:python: .ph data-hd-programlang='python'}
{:swift: .ph data-hd-programlang='swift'}


# Language support
{: #language-support}

{{site.data.keyword.knowledgestudiofull}} for {{site.data.keyword.icp4dfull_notm}} provides support for training a model in several languages.

Support for multiple languages does not mean that the product itself is translated. The {{site.data.keyword.knowledgestudioshort}} user interfaces, messages, and documentation are available in English only.
{: shortdesc}

You can train a model in the following languages:

- English (the default language)
- Arabic
- Brazilian Portuguese
- Chinese (Simplified)
- Chinese (Traditional)
- Dutch
- French
- German
- Italian
- Japanese
- Korean
- Spanish

Support includes the ability to add documents in these languages to a workspace, add dictionaries, run pre-annotation, use the ground truth editor to annotate documents, and train a machine learning model. When you select a language, the system applies language-specific templates to handle dictionary entries, text tokenization, and sentence segmentation. For information about how the system handles dictionaries in different languages, see [Dictionaries](/docs/watson-knowledge-studio-data?topic=watson-knowledge-studio-data-dictionaries#wks_dictionaries).

> **Note:** The rule editor and rule-based model cannot handle bidirectional text, so cannot be used with Arabic documents.

> **Restrictions:**
>
> Because of character restrictions in the underlying machine learning technology, entries in the type system cannot contain spaces and can include only the following ASCII characters:
>
> - A through Z and a through z
> - 0 through 9
> - The underscore character: _
>
> The following rules also apply:
>
> - The first character in the name must be alphabetical.
> - The entity type name length cannot exceed 64 characters.
> - The relation type name length cannot exceed 128 characters.
>
> Thus, for example, when a human annotator annotates Japanese text in the ground truth editor, the entity type and relation type names that can be applied will not be in Japanese.

### Related tasks

[Configuring support for Arabic](/docs/watson-knowledge-studio-data?topic=watson-knowledge-studio-data-wks_langsupp_ar)
