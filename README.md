# simpleJsAjaxFormSender
this is a simple ajax sender for forms.

<a href=#>form syntax</a>

class='__postAjaxForm__'   
    onPostStart='__FUNCTION_NAME__'     :: this is on progress start will run function name.  
    onPosting='__FUNCTION_NAME__'     :: this is on progress start will run function name.  When upload a file you can use this.  
    onPostEnd='__FUNCTION_NAME__'  :: this is when progressing will end will run function name.  
    onPostDone='__FUNCTION_NAME__'     :: this is on post success will run function name.  
    onPostFail='__FUNCTION_NAME__'     :: this is on post fail will run function name.  

<a href=#>input syntax</a>  
    __data-send="1"__ ::   if you want to send this data with ajax. You use data-send=1

<a href=#>submit button syntax</a>  
    class=__postAjaxButton__   :: You must use this class for sending form datas with simpleAjaxFormSender.







