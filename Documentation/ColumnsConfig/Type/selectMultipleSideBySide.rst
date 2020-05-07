.. include:: ../../../Includes.txt

.. _columns-select-rendertype-selectMultipleSideBySide:

===============================================
select: renderType = 'selectMultipleSideBySide'
===============================================

This page describes the :ref:`type='select' <columns-select>` with
renderType='selectMultipleSideBySide'.

Two select fields, items can be selected from the right field, selected items are displayed in the left select.

Examples
========

.. figure:: ../../Images/TypeSelectStyleguideMultipleSideBySide5.png
   :alt: Side-by-side view with filter (select_multiplesidebyside_5)
   :class: with-shadow

   Side-by-side view with filter (select_multiplesidebyside_5)


.. code-block:: php

        'select_multiplesidebyside_5' => [
            'label' => 'select_multiplesidebyside_5 multiSelectFilterItems',
            'config' => [
                'type' => 'select',
                'renderType' => 'selectMultipleSideBySide',
                'items' => [
                    ['foo 1', 1],
                    ['foo 2', 2],
                    ['foo 3', 3],
                    ['bar', 4],
                ],
                'multiSelectFilterItems' => [
                    ['', ''],
                    ['foo', 'foo'],
                    ['bar', 'bar'],
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

.. include:: ../Properties/CommonFieldControl.rst.txt
.. include:: ../FieldControl/AddRecord.rst.txt
.. include:: ../FieldControl/EditPopup.rst.txt
.. include:: ../FieldControl/ListModule.rst.txt

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

.. _columns-select-properties-multiselectfilteritems:
.. include:: ../Properties/SelectMultiSelectFilterItems.rst.txt

.. include:: ../Properties/CommonReadOnly.rst.txt

.. include:: ../Properties/CommonSize.rst.txt

.. include:: ../Properties/SelectSpecial.rst.txt
