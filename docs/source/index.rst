Resource naming guide
###########

Overview
**********

| Often, we need to give a name to this resource, a label that will help us understand and explain what it is.
| Resources, such as `files`, `servers`, `tables`, `fields`, `events` in web analytics, `documents`, `business concepts`, `terms`, `metrics`, etc  - represent elements or objects used in information systems or software for storing, processing, transmitting, or presenting data.
| Resources need names so that we can find, describe, reuse, refer to, or link to them, record who owns them, and interact with them in other ways. 
| But naming is not just a matter of assigning a sequence of characters. 
| In various fields, the names given to resources are influenced by rules, industry norms, or technological factors.
| We will discuss some naming issues and principles that help us name things in useful ways.

Why is this so important?

| Naming can be related to our understanding of the essence of things. This becomes clear when we use names that accurately describe or capture the main aspects of a subject. 
| This can help not only in precise identification but also in creating a deeper awareness of relationships and interactions in the studied subject area.

.. note::
   | "Now the Lord God had formed out of the ground all the wild animals and all the birds in the sky. 
   | He brought them to the man to see what he would name them; and whatever the man called each living creature, that was its name."
   | *Genesis 2:19*

   | Assigning names in this context has symbolic significance. In ancient societies, a name was extremely important.
   | By giving Adam the ability to name the animals, God demonstrates trust and faith in his ability to perceive and understand the world. 
   | The process of naming animals can also be interpreted as a gift of participation and management to humans.
   | It represents an opportunity for humans to demonstrate care and knowledge about the world around them, emphasizing responsibility for the surrounding world.

Assigning names to anything, from business to concepts and actions, can be a difficult process, and it can be done well or poorly.


Naming issues
**********


Ambiguity and the problem of vocabulary
===========

| There's no absolute best word to name something - this is known as the vocabulary issue.
| Natural languages give many options to express ideas. Typically, there are multiple words to represent the same object or concept.
| People choose to name or describe things based on their experience and context, so they often disagree about the words they use. 
| This often surprises people because what feels like a natural name to one person might not feel the same to someone else.


Homonymy, polysemy, and false cognates
===========

| Words that sound alike, words with multiple meanings, and words that look similar but mean different things
| Sometimes, the same word can refer to different resources: ``bank`` can mean a financial institution or the edge of a river. 
| Resources with names that sound alike or have many meanings can be mistaken or incorrectly identified, especially by automated processes that cannot use common sense or context. 

| When a word means something else in another language, it can result in humor or serious problems.
| ``Gift`` in German means ``poison`` and ``pain`` in French means ``bread``.


Names with unwanted associations
===========

False cognates can lead to poor names and marketing mistakes. 

.. note::
   For instance, numbers may carry different associations in various cultures: in one culture, the number 8 is valued for its association with wealth, while in another, the number 4 is feared due to its connection to death, or buildings skip the 13th floor in Western cultures due to superstitions. 

Some products have problems because of language differences.

.. note::
   For example, the Mitsubishi Pajero had negative connotations in the Spanish language, so in the USA, It's called the Montero to prevent negative associations and uphold a positive image.

Ignoring biases and ideas about names might seem okay, but it can cause big problems.


Discrimination
===========

Organizing resources alphabetically might appear equitable, yet it can create systematic bias in favor of names starting with early alphabet letters.
This sets up a scenario where resources listed earlier gain an advantage, overlooking the merits and potential of others.


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

Names such as ``IMG30467.jpg`` on a digital photo might make sense for the camera during sequential image storage, but they are inconvenient for humans. 
We prefer names that describe the content of the image, for instance, ``MyBeautifulGarden.jpg``


Long names
===========

Very long names can be hard to use and make the code look messy.
Adding too much information to names can make them confusing and repeat things.


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


Unclear abbreviations and acronyms
===========

| The problem of unclear abbreviations arises when projects or teams use abbreviations or acronyms that are not explained or widely known.
| This can lead to misunderstanding among team members, confusion within the project, and even conflicts due to different interpretations of the abbreviations.

For example, the abbreviation **JK** might refer to an employee, John Kowalski, but not everyone will understand it. **PM** could mean Project Manager or Product Marketing, causing confusion in context.

Acronyms like:
   * ``PDCA`` -> Plan-Do-Check-Act
   * ``TPS`` -> Transactions Per Second
   * ``SPA`` -> Single Page Application
   * ``DNA`` -> Deoxyribonucleic Acid
   * ``STEM`` -> Science, Technology, Engineering, Mathematics
   * ``CAGR`` -> Compound Annual Growth Rate
may be unclear to non-professionals or newcomers
   

Unclear names
===========

Names that don't show what something is can make it hard to use and cause mistakes or slow work down.

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

| The most fundamental principle in naming is to select informative names that facilitate understanding.
| Use names that are intuitive and easy to remember.
| Avoid using generic or universal names.


Avoid overly long names
===========

| This rule says that really long names make it hard to understand and can reduce work efficiency. 
| Also, shorter names mean there's less chance of having two names that are the same but in a different order of words.
| This naming rule is like to **Occam's razor**, suggesting that the simplest solution is often the best.
| It's important to make names shorter to its core meaning by removing unnecessary words or phrases.

.. tip::
   | calculate_total_sum_of_items_in_shopping_cart_and_apply_discount_and_add_tax
   | ↓
   | **calculate_final_cost**

   | employeeSalaryIncreaseAfterTaxAndDeductions
   | ↓
   | **netSalary**

   | Plan for project execution based on risk analysis and accounting for internal factors
   | ↓
   | **Adaptive project execution plan**

   | introduction_to_the_card_issuance_process
   | ↓
   | **card_issue_intro**

| Identify the main keywords or concepts most important for describing an object or process. 
| Then use them in a brief manner. If details or specifications are not crucial for understanding, they can be simplified or excluded from the name. 
| There's also a technique known as **shrinking to sense** or **reducing to ultimate meaning**. 
| It means systematically removing words or parts of a phrase while retaining the core meaning, stopping when further removal would cause loss of sense.

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
| Using naming rules makes code or systems look the same and easy to read. This helps people work together and share information among developers, analysts, and other project participants.

Standards and conventions may specifically relate to formatting, like selecting a preferred style for compound names.

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

Rules can also relate to the order of compound words and their suffixes and prefixes.

.. tip::
  | For example, consistently using the word 'intro' at the end when naming screens in a mobile application: 
  | `splash_intro`, `select_country_intro`, `select_product_intro`, `verify_income_intro`, `account_app_intro`, `card_issue_intro`, etc. 
  | It's essential to maintain uniformity.

For complex systems like data warehouses, conventions are often developed using semantic rules to explain the object's meaning by its name.

| The *COAST GUARD DATA ELEMENT NAMING STANDARDS* serve as an excellent example.
| The data object name consists of terms divided into three categories: 

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

``Modifiers``:
  | Add a description contained in the prime word and classifying words.
  | Provide clarity and uniqueness to the data object name.
  | Adjust the prime word and classifying words.
  | Limit the meaning of the classifying words and prime words.
  | For example: ``FIRST``, ``LAST``, ``NEXT``, ``BEGIN``, ``END``, ``MAX``, ``MIN``

For complex attribute names in a database table, the sequence might look like this:

.. figure:: /_static/attribute.png
   :width: 150%
   :align: center
   :alt: attribute naming rule

The root part of the attribute name is the class word, which classifies the type of information being represented by the attribute.

e.g.: PERMANENT_EMPLOYEE_LAST_NAME
  | NAME -> Class Word
  | LAST -> Modifier 2
  | EMPLOYEE -> Prime Word
  | PERMANENT -> Modifier 1

| Abbreviations and acronyms might be used, and then the field name could appear as PERM_EMPL_LST_NAME which is still readable and understandable.
| This technique was previously used when there were stricter limitations on name lengths in databases like a 30-character limit.

Avoid abbreviations and acronyms
**********
| Names should be spelled out entirely whenever possible instead of using abbreviations or acronyms. 
| Abbreviations can cause confusion or ambiguity and might not be universally understood by all team members or stakeholders, especially newcomers.

However, established domain-specific abbreviations or acronyms that are universally clear within the field are possible:

* API -> application programming interface
* ROI -> return on investment
* KPI -> key performance indicator
* CRM -> customer relationship management

Document your names
**********
| When necessary, explain the names and their meanings to the team members. 
| The technique of documenting names involves providing explanations for names, especially if they might not be obvious or contain specific meanings. 
| This helps stakeholders better understand the context and purpose of usage.

For instance:

``calculate_tax``
  The name itself might be good, but adding a description clarifies which tax is being calculated.
``order_status``
  Adding a description can specify possible status values and their meanings.
``employee_salary``
  A more detailed explanation could include how an employee's salary is calculated and what parameters are considered.


Use controlled vocabularies
**********

| One way to encourage the creation of good names for specific resource areas or tasks is by establishing a controlled vocabulary. 
| A controlled vocabulary is similar to a fixed or closed dictionary that includes terms used in a particular domain. 
| It reduces the number of words used, minimizes synonymy and homonymy, eliminates undesirable associations, and retains a set of words with clearly defined meanings and rules for their use.

| A controlled vocabulary is not only a set of allowed words; it also includes their definitions and often determines the rules by which dictionary terms can be used and combined. 


Context
**********

| When naming, consider the context in which names are used. 
| Ensure that the names make sense within the larger system or process.

| Use language specific to your business domain or knowledge familiar to your users or stakeholders. 
| For example:
* Oxford, Dictionary of Finance and Banking
* Forbes, A Glossary Of Basic Banking Terms


Allow aliasing
**********

A controlled vocabulary is highly beneficial for those who use it, but when designing an organizational system for others who might not use or understand it, you need to consider the diversity of words they might use when searching or describing resources.

For instance, the official name of a particular fish species is *"Amphiprion ocellaris"*, but most people would search for it as *"clownfish"*, *"anemone fish"*, or even by its more popular name from the movie Nemo.

A related mechanism used by search systems is spell-checking, where all misspellings are treated as aliases for the correct term ("Did you mean California?" when you typed Califorina").


Make names unique or qualified
**********

| While a name refers to one resource, it doesn't mean that two names cannot be identical.
| Each name or identifier should be unique within its accounting system. 
| We can prevent or reduce conflicts by adding information about the namespace or domain from which names or identifiers are chosen, creating what is often referred to as fully qualified names.
| For instance, in the United States, there are several dozen cities named "Springfield" and "Washington," but adding state codes to postal addresses distinguishes between them.


Use reserved words cautiously
**********

| Avoid using reserved words in programming languages or other platform constraints.
| Reserved words are those that hold special meaning within a programming language and cannot be used as variable names, function names, class names, and so on.
| These words usually reflect the syntax and semantics of the language, defining the structure and logic of a program.

| In SQL, reserved words include terms like ``SELECT``, ``FROM``, ``WHERE``, ``JOIN``, ``GROUP BY``, ``ORDER BY``, and more. 
| These words are used for querying databases and manipulating data.

| In Python, reserved words include ``if``, ``else``, ``while``, ``for``, ``import``, ``def``, ``class``, ``try``, ``except``, and others.
| These words are used for defining conditions, loops, functions, classes, exceptions, and various aspects of a program.


Versioning, modifications, and dates
**********

Incorporating versions into document names or dates into file names can assist in identifying chronological order and aid in search and sorting.

| It's recommended to use dates in the ISO8601 standard format ``YYYY-MM-DD``. 
| For instance:
| "2021-08-02 v2 Policies and procedures"

Additionally, different stages or statuses of a document or process can be denoted such as ``vDraft``, ``vFinal``, ``vExecuted``, ``vPreRead``, etc.


Name testing
**********

| Test names for readability, clarity, and relevance to the context.

| One way to avoid surprises is to engage people in collaborative efforts when choosing names for resources.
| Information architects often use collective design methods for this purpose, such as card sorting or free placement.

.. toctree::
  :caption: Table of Contents
  :numbered:
