.. include:: ../../../Includes.txt

.. _columns-select-rendertype-selectSingleBox:

======================================
select: renderType = 'selectSingleBox'
======================================

This page describes the :ref:`type='select' <columns-select>` with
renderType='selectSingleBox'.

Renders a select field to select multiple entries from a given list.

.. important::

   The name is misleading. This is a renderType which allows you to select
   **multiple** elements!

Examples
========

.. figure:: ../../Images/TypeSelectStyleguideSingleBox1.png
   :alt: Select multiple values from a box (select_singlebox_1)
   :class: with-shadow

   Select multiple values from a box (select_singlebox_1)

.. code-block:: php

        'select_singlebox_1' => [
            'label' => 'select_singlebox_1',
            'config' => [
                'type' => 'select',
                'renderType' => 'selectSingleBox',
                'items' => [
                    ['foo 1', 1],
                    ['foo 2', 2],
                    ['divider', '--div--'],
                    ['foo 3', 3],
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

.. include:: ../Properties/CommonAutoSizeMax.rst.txt

.. include:: ../Properties/CommonBehaviour.rst.txt
.. include:: ../Behaviour/CommonAllowLanguageSynchronization.rst.txt

.. include:: ../Properties/SelectDefault.rst.txt

.. include:: ../Properties/SelectDisableNonMatchingValueElement.rst.txt

.. include:: ../Properties/CommonDontRemapTablesOnCopy.rst.txt

.. include:: ../Properties/SelectExclusiveKeys.rst.txt

.. _columns-select-properties-fieldControl:
.. include:: ../Properties/CommonFieldControl.rst.txt
.. include:: ../Properties/ResetSelection.rst.txt

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

.. _columns-select-properties-maxitems:
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
