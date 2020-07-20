# editable_dropdown

An application to determine the best approach [for me] to creating an editable dropdown list (form field).


Using the package [dropdown_suggestions_form_field](https://pub.dev/packages/dropdown_suggestions_form_field), I was able to style and configure everything necessary to get the widget to fit into the styling of my application and provide the functionality.  The only 'negative' comment I have is that two of the attributes of the Widget seem to be a little out of sync to me:

suggestionNotMatch: null
	This seems to have no effect on the UI.  Should it disable the NoMatch message?
	
suggestionNotMatchMessage: null
	This throws a null exception. OK, but using ' ' to disable the default message seems a little off to me.


Other packages used include:
- [provider](https://pub.dev/packages/provider)
- [shared_preferences](https://pub.dev/packages/shared_preferences)
- [sized_context](https://pub.dev/packages/sized_context)
