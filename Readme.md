# How to customize columns order and visibility in a custom drop-down menu


<p>This example shows how to create a <a href="http://documentation.devexpress.com/#WindowsForms/clsDevExpressXtraGridViewsGridGridViewtopic">GridView</a> descendant that will allow users to customize columns order an visibility in a new drop-down menu. This drop-down menu allows hiding columns by the check box checking or un checking, and change columns order simply by items dragging. </p><p>The drop-down menu can be invoked by clicking the quick customization button, which is placed on the column button. <br />
This menu can be disabled by specifying the <strong>GridView.OptionsCustomization.AllowQuickCustomizations</strong> property. You can use the <strong>GridView.OptionsCustomization.QuickCustomizationIcon</strong> property to specify an image, displayed on the quick customization button. <br />
Keep in mind that, not all the columns can be moved or hidden in compliance with <a href="http://documentation.devexpress.com/#WindowsForms/clsDevExpressXtraGridViewsGridGridViewtopic">GridView</a> and <a href="http://documentation.devexpress.com/#WindowsForms/clsDevExpressXtraGridColumnsGridColumntopic">GridColumn</a> options.<br />
The column moving capability can be disabled by setting the <a href="http://documentation.devexpress.com/#WindowsForms/DevExpressXtraGridViewsGridGridOptionsCustomization_AllowColumnMovingtopic">GridView.OptionsCustomization.AllowColumnMoving</a> and <a href="http://documentation.devexpress.com/#WindowsForms/DevExpressXtraGridColumnsOptionsColumn_AllowMovetopic">GridColumn.OptionsColumn.AllowMove</a> properties to <i>False</i>. A column cannot be hidden if the <a href="http://documentation.devexpress.com/#WindowsForms/DevExpressXtraGridViewsGridGridOptionsCustomization_AllowQuickHideColumnstopic">GridView.OptionsCustomization.AllowQuickHideColumns</a> or <strong>GridColumn.OptionsColumn.AllowQuickHide</strong> property has the <i>False</i> value. The <strong>GridColumn.OptionsColumn.AllowQuickHide</strong> property is a new property, implemented in this descendant only. If a column's <a href="http://documentation.devexpress.com/#WindowsForms/DevExpressXtraGridColumnsOptionsColumn_ShowInCustomizationFormtopic">GridColumn.OptionsColumn.ShowInCustomizationForm</a> property has the <i>False</i> value, this column will be displayed in the column customization drop-down menu only when it is visible.</p><p><strong>See Also:</strong><br />
<a href="https://www.devexpress.com/Support/Center/p/K18345">How to add a quick columns customization drop-down menu to a GridView</a></p>

<br/>


