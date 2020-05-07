.. include:: ../../../Includes.txt

.. _columns-select-rendertype-selectCheckBox:

=====================================
select: renderType = 'selectCheckBox'
=====================================

This page describes the :ref:`type='select' <columns-select>` with
renderType='selectCheckBox'.

Render the list of values as single check box rows in a table. Multiple items can be selected.

Examples
========

.. figure:: ../../Images/TypeSelectStyleguideCheckbox3.png
   :alt: Select values from a checkbox list (select_checkbox_3)
   :class: with-shadow

   Select values from a checkbox list (select_checkbox_3)


.. code-block:: php

        'select_checkbox_3' => [
            'label' => 'select_checkbox_3 icons, description',
            'config' => [
                'type' => 'select',
                'renderType' => 'selectCheckBox',
                'items' => [
                    ['foo 1', 1, '', 'optional description'],
                    ['foo 2', 2, 'EXT:styleguide/Resources/Public/Icons/tx_styleguide.svg', 'description'],
                    ['foo 3', 3, 'EXT:styleguide/Resources/Public/Icons/tx_styleguide.svg'],
                    ['foo 4', 4],
                ],
            ],
        ],



Properties
==========

.. contents::
   :local:
   :depth: 1


.. include:: ../Properties/SelectAllowNonIdValues.rst.txt

.. include:: ../Properties/SelectAuthMode.rst.txt

.. include:: ../Properties/SelectAuthModeEnforce.rst.txt

.. include:: ../Properties/CommonBehaviour.rst.txt
.. include:: ../Behaviour/CommonAllowLanguageSynchronization.rst.txt

.. include:: ../Properties/SelectDefault.rst.txt

.. include:: ../Properties/SelectDisableNonMatchingValueElement.rst.txt

.. include:: ../Properties/CommonDontRemapTablesOnCopy.rst.txt

.. include:: ../Properties/SelectExclusiveKeys.rst.txt

.. include:: ../Properties/CommonFieldInformation.rst.txt

.. include:: ../Properties/CommonFieldWizard.rst.txt
.. include:: ../FieldWizard/DefaultLanguageDifferences.rst.txt
.. include:: ../FieldWizard/LocalizationStateSelector.rst.txt
.. include:: ../FieldWizard/OtherLanguageContent.rst.txt

.. include:: ../Properties/SelectFileFolder.rst.txt

.. include:: ../Properties/SelectFileFolderExtList.rst.txt

.. include:: ../Properties/SelectFileFolderRecursions.rst.txt

.. include:: ../Properties/SelectForeignTable.rst.txt

.. include:: ../Properties/SelectForeignTablePrefix.rst.txt

.. include:: ../Properties/SelectForeignTableWhere.rst.txt

.. include:: ../Properties/SelectItems.rst.txt

.. include:: ../Properties/CommonItemsProcFunc.rst.txt

.. include:: ../Properties/CommonLocalizeReferencesAtParentLocalization.rst.txt

.. include:: ../Properties/CommonMaxitems.rst.txt

.. include:: ../Properties/CommonMinitems.rst.txt

.. include:: ../Properties/CommonMm.rst.txt

.. include:: ../Properties/CommonMmHasUidField.rst.txt

.. include:: ../Properties/CommonMmInsertFields.rst.txt

.. include:: ../Properties/CommonMmTableWhere.rst.txt

.. include:: ../Properties/CommonMmMatchFields.rst.txt

.. include:: ../Properties/CommonOppositeField.rst.txt

.. include:: ../Properties/CommonMmOppositeUsage.rst.txt

.. include:: ../Properties/CommonMultiple.rst.txt

.. include:: ../Properties/CommonReadOnly.rst.txt

.. include:: ../Properties/CommonSize.rst.txt

.. include:: ../Properties/SelectSpecial.rst.txt
