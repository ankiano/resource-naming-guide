Resource naming guide
###########

Overview
**********

| Often, we need to give a name to this resource, a label that will help us understand and explain what it is.
| Resources, such as `files`, `servers`, `tables`, `fields`, `events` in web analytics, `documents`, `business concepts`, `terms`, `metrics`, etc  - represent elements or objects used in information systems or software for storing, processing, transmitting, or presenting data.
| Resources need names so that we can find, describe, reuse, refer to, or link to them, record who owns them, and interact with them in other ways. But naming is not just a matter of assigning a sequence of characters. 
| In many domains, names assigned to resources also depend on or are limited by rules, industry practice, or technological considerations.
| We will discuss some naming issues and principles that help us name things in useful ways.

Why is this so important?

| Naming can be related to our understanding of the essence of things, and this is evident when we use names that best describe or capture the key aspects of the subject. 
| This can help not only in precise identification but also in creating a deeper awareness of relationships and interactions in the studied subject area.

.. note::
   "Now the Lord God had formed out of the ground all the wild animals and all the birds in the sky. 
   He brought them to the man to see what he would name them; and whatever the man called each living creature, that was its name."
   Genesis 2:19

   | Assigning names in this context has symbolic significance. In ancient societies, a name was extremely important.
   | By giving Adam the ability to name the animals, God demonstrates trust and faith in his ability to perceive and understand the world. 
   | The process of naming animals can also be interpreted as a gift of participation and management to humans.
   | It represents an opportunity for humans to demonstrate care and knowledge about the world around them, emphasizing responsibility for the surrounding world.

Assigning names to anything, from business to concepts and actions, can be a difficult process, and it can be done well or poorly.


Naming issues
**********


Ambiguity and the problem of vocabulary
===========

| No single word can be considered the **best** name - this phenomenon is referred to as the problem of vocabulary.
| Every natural language offers several ways to express any thought, and in particular, there are usually multiple words that can be used to denote the same object or concept. 
| People choose to name or describe things based on their experience and context, so they often disagree about the words they use. 
| Furthermore, people are often surprised when this happens because what seems natural or obvious as a name to one person is not natural or obvious to another.


Homonymy, polysemy, and false cognates
===========

| Sometimes, the same word can refer to different resources: 'bank' can mean a financial institution or the edge of a river. 
| When two words have the same spelling but different meanings, they are called homographs; if they are also pronounced the same way, they are homonyms. 
| When different meanings of homographs are related, it's called polysemy.

| Resources with homonymous and polysemous names are sometimes incorrectly identified, especially by automated processes that cannot use common sense or context. 
| When a word in one language has a different meaning and refers to different resources in another language, it can be funny or catastrophically harmful. 
| ``Gift`` in German means ``poison`` and ``pain`` in French means ``bread``.


Names with unwanted associations
===========

False cognates can lead to poor names and marketing mistakes. 

.. note::
   For instance, numbers may carry different associations in various cultures: in one culture, the number 8 is valued for its association with wealth, while in another, the number 4 is feared due to its connection to death, or buildings skip the 13th floor in Western cultures due to superstitions. 

Some products face issues due to linguistic peculiarities. 

.. note::
   For example, the Mitsubishi Pajero had negative connotations in the Spanish language, so in the USA, it's called the Montero to avoid undesirable associations and maintain a positive perception.

Ignoring biases and preconceptions about names and identifiers might seem harmless, but the consequences are far-reaching and anything but harmless. 


Discrimination
===========

Ordering resources alphabetically, while seemingly fair, can lead to systematic discrimination in favor of names starting with letters at the beginning of the alphabet. 
This creates a context where resources listed earlier might receive an advantage, ignoring the merits and potential of others.


Names that assume impermanent attributes
===========

Many resources are given names based on attributes that can become problematic later if the value or interpretation of the attribute changes.

.. note::
   "Kentucky Fried Chicken" started in 1930 as a small cafe in Corbin, Kentucky, becoming one of the first international fast-food chains. In 1987, they opened their first restaurant in China and soon shortened the name to "KFC," considering that many outside Kentucky, such as Beijing or London, might not be familiar with their location.

Some companies use dates or years in their names to indicate a future orientation.

.. note::
   For example, the film studio "20th Century Fox" chose this name in the 1930s for its progressive and forward-thinking identity, but today, such a name might have the opposite effect.


The semantic gap
===========

| The semantic gap refers to a lack of understanding of information stored in data. 
| This lack of understanding can vary among users or between users and data creators.
| It arises from differences in describing and naming resources when automated processes use technical but uninformative labels that differ from human preferences.

Names such as ``IMG30467.jpg`` on a digital photograph might make sense for the camera during sequential image storage, but they are inconvenient for humans. 
We prefer names that describe the content of the image, for instance, ``MyBeautifulGarden.jpg``


Long names
===========

Names that are excessively long can be inconvenient to use and visually clutter the code. 
Adding unnecessary details to object names can lead to redundancy and confusion.


Inconsistency
===========

The lack of a unified naming style leads to confusion within a project or across projects.

.. note::
   In 2008, Last.fm's music recommendations employee Richard Jones compiled a list of the 100 most frequently described recordings of Guns N' Roses' cover of Bob Dylan's song 'Knockin' on Heaven's Door


.. code-block:: concole
   :caption: Top 25 Representations of "Knockin' On Heaven's Door"
   :linenos:

    Guns N' Roses - Knockin' On Heaven's Door
    Guns N' Roses - Knocking On Heavens Door
    Guns 'N' Roses - Knockin On Heaven's Door
    Guns N' Roses - Knockin On Heavens Door
    Guns N' Roses - Knockin' On Heavens Door
    Guns N'roses - knockin on heavens door
    Guns N' Roses - Knocking On Heaven's Door
    Guns N Roses - Knockin' On Heaven's Door
    Guns N Roses - Knockin On Heavens Door
    Guns And Roses - Knocking On Heavens Door
    Guns Nroses - Knockin On Heavens Door
    Guns'n' Roses - Knockin' On Heaven's Door
    Guns N Roses - Knocking On Heavens Door
    Guns'n'Roses - Knockin' On Heaven's Door
    Guns 'N Roses - Knockin' On Heaven's Door
    Guns & Roses - Knockin' on Heaven's Door
    Guns N'roses - Knockin' On Heaven's Door
    Guns and Roses - Knockin' On Heaven's Door
    Guns n Roses - Knocking On Heavens Door
    Guns 'n' Roses - Knockin' On Heavens Door
    Aerosmith - Knocking On Heaven's Door
    Guns 'n Roses - Knocking On Heaven's Door
    Guns 'n' Roses - Knocking On Heavens Door
    Guns N Roses - Knocking On Heaven's Door
    Guns N' Roses - Heaven's Knockin On Door

The inconsistent use of upper and lower case makes names less readable and harder to identify.

  .. code-block:: concole

    ├── Documents
        ├── best_practice
        ├── important-item
        ├── InterestingTopic
        ├── myFile
        ├── new-element
        ├── OurData
        ├── randomKey
        ├── small-project
        └── your_resource


Unclear Abbreviations and Acronyms
===========

| The problem of unclear abbreviations arises when projects or teams use abbreviations or acronyms that are not explained or widely known.
| This can lead to misunderstanding among team members, confusion within the project, and even conflicts due to different interpretations of the abbreviations.

For example, the abbreviation **JK** might refer to an employee, John Kowalski, but not everyone will understand it. **PM** could mean Project Manager or Product Marketing, causing confusion in context.

Acronyms like:
   * ``PDCA`` (Plan-Do-Check-Act)
   * ``TPS`` (Transactions Per Second)
   * ``SPA`` (Single Page Application) 
   * ``DNA`` (Deoxyribonucleic Acid)
   * ``STEM`` (Science, Technology, Engineering, Mathematics)
   * ``CAGR`` (Compound Annual Growth Rate)
may be unclear to non-professionals or newcomers
   

Ambiguous Names
===========

Names that fail to reflect the essence of a resource or object can impede understanding, usage, and lead to errors or delays in work.

``temp``
  This name might be used for temporary variables in code, tables, or directories, but it doesn't provide information about what exactly is stored in this variable or what it's used for.
``misc``
  An abbreviation for 'miscellaneous,' often used to group various items. However, this name is not informative, failing to indicate the specific components or purpose of this group.
``data``
  The name 'data' might be used for various datasets, but by itself, it doesn't convey the nature or format of these data.
``new``
  These names can become problematic over time as they remain undefined and become less informative when the **newness** fades or another version emerges. 
  In some cases, you might encounter abbreviations like **new_new** or **newer**, indicating something was new but has now become outdated or replaced by a newer version.


Choosing good names and identifiers
**********


Make names informative
===========

| The most fundamental principle in naming is to select informative names that facilitate understanding and memorization.
| Use names that are intuitive and easy to remember.
| Avoid using generic or universal names.


Avoid overly long names
===========

| This principle is based on the idea that excessively long names complicate information perception and can reduce work efficiency. 
| Additionally, shorter names minimize the risk of duplicates from word rearrangement.
| This naming rule is like to **Occam's razor**, suggesting that the simplest solution is often the best.
| It's important to condense the name to its core meaning by removing unnecessary words or phrases.

.. tip::
   | calculate_total_sum_of_items_in_shopping_cart_and_apply_discount_and_add_tax
   | ↓
   | **calculate_final_cost**

   | employeeSalaryIncreaseAfterTaxAndDeductions
   | └── **netSalary**

   | Plan for project execution based on risk analysis and accounting for internal factors
   | └── **Adaptive project execution plan**

   | introduction_to_the_card_issuance_process
   | └── **card_issue_intro**

| Identify the main keywords or concepts most important for describing an object or process. 
| Then use them in a concise format. If details or specifications are not crucial for understanding, they can be simplified or excluded from the name. 
| There's also a technique known as **shrinking to sense** or **reducing to ultimate meaning**. 
| It involves systematically removing words or parts of a phrase while preserving the core meaning, stopping when further removal would cause loss of sense.

.. tip::
   | You can progressively remove words:
   | For instance, let's consider the lengthy title
   | Adaptive project execution plan based on risk analysis and internal factors
   | └── Adaptive project execution plan based on risk analysis and internal factors
   |     └── Adaptive project execution plan based on risk analysis
   |         └── Adaptive project execution plan
   |             └── Project execution plan

  Continuing this way until the essential meaning is retained.


Consistency
**********

| Consistency is a characteristic that reflects the degree of stability, uniformity, or constancy in something. 
| Maintaining a unified naming style throughout a project or organization helps achieve this. 
| Applying naming standards that adhere to specific rules and conventions aids in creating uniform and easily readable code or a system, which, in turn, facilitates teamwork and information exchange among developers, analysts, and other project participants.

Rules and styles can pertain to format only, for instance, choosing one of the standards for compound names:
``camelCase``
  Each new word starts with a capital letter, without spaces. Example: myVariableName, calculateInterestRate.
``PascalCase``
  Similar to camelCase, but the first letter is also capitalized. Commonly used for class and data type names. Example: MyClass, CalculateInterest.
``snake_case``
  Words are separated by an underscore, usually in all lowercase letters. Example: my_variable_name, calculate_interest_rate.
``kebab-case``
  Words are separated by a hyphen, generally in all lowercase. Often used in URLs and file names. Example: my-variable-name, calculate-interest-rate.
``MixedCase``
  Represents a mixed style where different parts of words may have different cases. Example: iOSDevelopment, JavaScriptProgramming.

Rules can also pertain to the order of compound words and their suffixes and prefixes. 
.. tip::
  | For example, consistently using the word 'intro' at the end when naming screens in a mobile application: 
  | `splash_intro`, `select_country_intro`, `select_product_intro`, `verify_income_intro`, `account_app_intro`, `card_issue_intro`, etc. 
  | It's essential to maintain uniformity.

For complex systems like data repositories, conventions are often developed using semantic rules to explain the object's meaning by its name.

| The *COAST GUARD DATA ELEMENT NAMING STANDARDS* serve as an excellent example.
| The data object name consists of terms divided into three categories: 
* the prime word
* classifying word
* and modifiers (determiners).

``Prime Words``:
  | Nouns or phrases describing the subject or primary meaning of the name.
  | Show the data element's place in the logical context of the information model.
  | For example: ``PARTY``, ``DEAL``, ``CLIENT``, ``EMPLOYEE``, ``CURRENCY``
  | The prime word imparts meaning to the attribute name, providing the right context for the modifier and classifying words. 
  | Although there is no standard list of prime words, terms commonly suitable as subjects are usually nouns, representing common things for any organization.
  | Furthermore, prime words may consist of multiple terms, but brevity is crucial to accommodate the rest of the nominal group within a reasonable name size.

``Classifying Words``:
  | Indicate categorical differentiation or classification of information.
  | Describe the main data category associated with the information element.
  | For example: ``DATE``, ``AMOUNT``, ``QUANTITY``, ``CODE``, ``NAME``, ``DESCRIPTION``, ``IDENTIFIER``, ``RATE``

``Modifiers`` (Determiners):
  | Add a description contained in the prime word and classifying words.
  | Provide clarity and uniqueness to the data object name.
  | Adjust the prime word and classifying words.
  | Limit the meaning of the classifying words and prime words.
  | For example: ``FIRST``, ``LAST``, ``NEXT``, ``BEGIN``, ``END``, ``MAX``, ``MIN``

For complex attribute (field) names in a database table, the sequence might look like this:

.. figure:: /_static/attribute.png
   :width: 150%
   :align: center
   :alt: attribute naming rule

The root part of the attribute name is the class word, which classifies the type of information being represented by the attribute.

e.g.: PERMANENT_EMPLOYEE_LAST_NAME
  | NAME - Class Word
  | LAST - Modifier 2
  | EMPLOYEE - Prime Word
  | PERMANENT - Modifier 1

| In data repositories, dictionaries of abbreviations and acronyms might be used, and then the field name could appear as PERM_EMPL_LST_NAME. 
| This technique was previously employed when there were stricter limitations on name lengths in databases - for instance, in Oracle, there was a 30-character limit.

Avoid Abbreviations and Acronyms
**********
| Names should be spelled out entirely whenever possible instead of using abbreviations or acronyms. 
| Abbreviations can cause confusion or ambiguity and might not be universally understood by all team members or stakeholders, especially newcomers.

However, established domain-specific abbreviations or acronyms that are universally clear within the field are permissible:

* API -> application programming interface
* ROI -> return on investment
* KPI -> key performance indicator
* CRM -> customer relationship management

.. toctree::
  :caption: Table of Contents
  :numbered:
