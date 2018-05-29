# Vanilla: Forms

Labels
- Text color: `$color-dark`
- Font size: `1rem`
- Margin bottom: `$sp-x-small`

Text input fields and texarea
- Background color: `$color-x-light`
- Border color: `$color-mid-light`
- Border style: solid
- Border width: 1px
- Border radius: 2px
- Padding top/bottom: `$sp-x-small`
- Padding left/right: `$sp-small`
- Unfocused:
  - Placeholder text color: `$color-mid-dark`
- Focused:
	- Text color: `$color-dark`
	- Border color: `$color-mid-dark`

Fieldset
- Background color: `$color-light`
- Border color: `$color-mid-light`
- Border style: solid
- Border width: 1px
- Border radius: 2px
- Padding: `$sp-small`
- Heading: heading-three
- Heading bottom border: 1px `$color-mid-light` solid
- Space between heading and heading border: `$sp-small`
- Space between consecutive field sets: `$sp-large`

Help text
- Text color: `$color-mid-dark`
- Font size: `0.875rem`
- Margin top: `$sp-x-small`

Validation
- Validation messages:
	- Text color: `$color-dark`
	- Font size: `0.875rem`
	- First word ("Error", "Warning") font weight: 400
	- Margin top: `$sp-x-small`
- Validation icons:
	- Position inside input field: 12px from top and right
- Success:
	- Input border color: `$color-positive`
	- Icon: `p-icon--success`
- Warning:
	- Input border color: `$color-warning`
	- Icon: `p-icon--warning`	
- Error:
	- Input border color: `$color-negative`
	- Icon: `p-icon--error`

Checkboxes
- Checkbox: browser default
- Margin right: `0.75rem`
- Text color: `$color-dark`
- Font size: `1rem`

Checkboxes disabled
- Opacity: .5
- Cursor: not allowed

Radio buttons
- Checkbox: browser default
- Margin right: `0.75rem`
- Text color: `$color-dark`
- Font size: `1rem`

Radio buttons disabled
- Opacity: .5
- Cursor: not allowed

Normal form layout
- This uses the existing vanilla form

Stacked form layout
- The text labels should use a max width of 3 cols
- Label aligned vertically centred to the field
- Spacing between fields: `$sp-medium` 
- Button is aligned right to the fields
- Spacing between last field and button: `1.25rem`

In line form layout
- Spacing between text labels and field: `$sp-medium`
- Spacing between field and next label: `$sp-large`
- Spacing between last field and button: `$sp-large`