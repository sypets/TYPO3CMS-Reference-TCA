.. include:: ../../../Includes.txt

.. _columns-select-rendertype-selectTree:

====================================
select: renderType = 'selectTree'
====================================

This page describes the :ref:`type='select' <columns-select>` with
renderType='selectTree'.

A tree for selecting hierarchical data items.

Examples
========

.. figure:: ../../Images/TypeSelectStyleguideTree1.png
   :alt: A happy little tree! (select_tree_1)
   :class: with-shadow

   A happy little tree! (select_tree_1)



.. code-block:: php

        'select_tree_1' => [
            'label' => 'select_tree_1 pages, showHeader=true, expandAll=true, size=20, order by sorting, static items',
            'config' => [
                'type' => 'select',
                'renderType' => 'selectTree',
                'foreign_table' => 'pages',
                'foreign_table_where' => 'ORDER BY pages.sorting',
                'size' => 20,
                'items' => [
                    ['static from tca 4711', 4711],
                    ['static from tca 4712', 4712],
                ],
                'treeConfig' => [
                    'parentField' => 'pid',
                    'appearance' => [
                        'expandAll' => true,
                        'showHeader' => true,
                    ],
                ],
            ],
        ],


Properties
==========

.. note::
    This section needs a validation of the single properties - probably some of the relation
    properties like MM are not valid.


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
.. include:: ../FieldWizard/LocalizationStateSelector.rst.txt

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

.. _columns-select-properties-treeconfig:
.. include:: ../Properties/SelectTreeConfig.rst.txt
