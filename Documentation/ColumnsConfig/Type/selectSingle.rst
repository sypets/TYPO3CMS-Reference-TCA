.. include:: ../../../Includes.txt

.. _columns-select-rendertype-selectSingle:

====================================
select: renderType = 'selectSingle'
====================================

This page describes the :ref:`type='select' <columns-select>` with
renderType='selectSingle'.

Select one element from a list of elements.


Examples
========

.. figure:: ../../Images/TypeSelectStyleguideSingle3.png
   :alt: Simple select drop down with static and database values (select_single_3)
   :class: with-shadow

   Simple select drop down with static and database values (select_single_3)

.. code-block:: php

        'select_single_3' => [
            'label' => 'select_single_3 static values, dividers, foreign_table_where',
            'config' => [
                'type' => 'select',
                'renderType' => 'selectSingle',
                'items' => [
                    ['Static values', '--div--'],
                    ['static -2', -2],
                    ['static -1', -1],
                    ['DB values', '--div--'],
                ],
                'foreign_table' => 'tx_styleguide_staticdata',
                'foreign_table_where' => 'AND {#tx_styleguide_staticdata}.{#value_1} LIKE \'%foo%\' ORDER BY uid',
                'foreign_table_prefix' => 'A prefix: ',
            ],
        ],


.. figure:: ../../Images/ColumnsExampleSelectImages.png
   :alt: Select foreign rows which have icons configured (select_single_12)
   :class: with-shadow

   Select foreign rows which have icons configured (select_single_12)


.. code-block:: php

        'select_single_12' => [
            'label' => 'select_single_12 foreign_table selicon_field',
            'config' => [
                'type' => 'select',
                'renderType' => 'selectSingle',
                'foreign_table' => 'tx_styleguide_elements_select_single_12_foreign',
                'fieldWizard' => [
                    'selectIcons' => [
                        'disabled' => false,
                    ],
                ],
            ],
        ],

.. figure:: ../../Images/TypeSelectStyleguideSingle10.png
   :alt: Select a single value from a list of elements (select_single_10)
   :class: with-shadow

   Select a single value from a list of elements (select_single_10)

.. code-block:: php

        'select_single_10' => [
            'label' => 'select_single_10 size=6, three options',
            'config' => [
                'type' => 'select',
                'renderType' => 'selectSingle',
                'items' => [
                    ['foo 1', 1],
                    ['foo 2', 2],
                    ['a divider', '--div--'],
                    ['foo 3', 3],
                ],
                'size' => 6,
            ],
        ],



.. _columns-select-properties:

Properties
==========

.. contents::
   :local:
   :depth: 1

.. _columns-select-properties-type:

.. _columns-select-properties-allownonidvalues:
.. include:: ../Properties/SelectAllowNonIdValues.rst.txt

.. _columns-select-properties-authmode:
.. include:: ../Properties/SelectAuthMode.rst.txt

.. _columns-select-properties-authmode-enforce:
.. include:: ../Properties/SelectAuthModeEnforce.rst.txt

.. _columns-select-properties-behaviour:
.. include:: ../Properties/CommonBehaviour.rst.txt
.. include:: ../Behaviour/CommonAllowLanguageSynchronization.rst.txt

.. _columns-select-properties-default:
.. include:: ../Properties/SelectDefault.rst.txt

.. _columns-select-properties-disablenomatchingvalueelement:
.. include:: ../Properties/SelectDisableNonMatchingValueElement.rst.txt

.. _columns-select-properties-dontremaptablesoncopy:
.. include:: ../Properties/CommonDontRemapTablesOnCopy.rst.txt

.. _columns-select-properties-exclusivekeys:
.. include:: ../Properties/SelectExclusiveKeys.rst.txt

.. _columns-select-properties-fieldInformation:
.. include:: ../Properties/CommonFieldInformation.rst.txt

.. _columns-select-properties-fieldWizard:
.. include:: ../Properties/CommonFieldWizard.rst.txt
.. include:: ../FieldWizard/DefaultLanguageDifferences.rst.txt
.. include:: ../FieldWizard/LocalizationStateSelector.rst.txt
.. include:: ../FieldWizard/OtherLanguageContent.rst.txt
.. include:: ../FieldWizard/SelectIcons.rst.txt

.. _columns-select-properties-filefolder:
.. include:: ../Properties/SelectFileFolder.rst.txt

.. _columns-select-properties-filefolder-extlist:
.. include:: ../Properties/SelectFileFolderExtList.rst.txt

.. _columns-select-properties-filefolder-recursions:
.. include:: ../Properties/SelectFileFolderRecursions.rst.txt

.. _columns-select-properties-foreign-table:
.. include:: ../Properties/SelectForeignTable.rst.txt

.. _columns-select-properties-foreign-table-prefix:
.. include:: ../Properties/SelectForeignTablePrefix.rst.txt

.. _columns-select-properties-foreign-table-where:
.. include:: ../Properties/SelectForeignTableWhere.rst.txt

.. _columns-select-properties-items:
.. include:: ../Properties/SelectItems.rst.txt

.. _columns-select-properties-itemsprocfunc:
.. include:: ../Properties/CommonItemsProcFunc.rst.txt

.. _columns-select-properties-localizereferencesatparentlocalization:
.. include:: ../Properties/CommonLocalizeReferencesAtParentLocalization.rst.txt

.. _columns-select-properties-minitems:
.. include:: ../Properties/CommonMinitems.rst.txt

.. _columns-select-properties-mm:
.. include:: ../Properties/CommonMm.rst.txt

.. _columns-select-properties-mm-hasuidfield:
.. include:: ../Properties/CommonMmHasUidField.rst.txt

.. _columns-select-properties-mm-insert-fields:
.. include:: ../Properties/CommonMmInsertFields.rst.txt

.. _columns-select-properties-mm-table-where:
.. include:: ../Properties/CommonMmTableWhere.rst.txt

.. _columns-select-properties-mm-match-fields:
.. include:: ../Properties/CommonMmMatchFields.rst.txt

.. _columns-select-properties-mm-opposite-field:
.. include:: ../Properties/CommonOppositeField.rst.txt

.. _columns-select-properties-mm-opposite-usage:
.. _columns-select-properties-mm-oppositeusage:
.. include:: ../Properties/CommonMmOppositeUsage.rst.txt

.. _columns-select-properties-multiple:
.. include:: ../Properties/CommonMultiple.rst.txt

.. _columns-select-properties-readOnly:
.. include:: ../Properties/CommonReadOnly.rst.txt

.. _columns-select-properties-showicontable:
.. include:: ../Properties/SelectShowIconTable.rst.txt

.. _columns-select-properties-size:
.. include:: ../Properties/CommonSize.rst.txt

.. _columns-select-properties-special:
.. include:: ../Properties/SelectSpecial.rst.txt



