# Loading Multibyte Data from Amazon S3<a name="copy-usage_notes-multi-byte"></a>

If your data includes non\-ASCII multibyte characters \(such as Chinese or Cyrillic characters\), you must load the data to VARCHAR columns\. The VARCHAR data type supports four\-byte UTF\-8 characters, but the CHAR data type only accepts single\-byte ASCII characters\. You cannot load five\-byte or longer characters into Amazon Redshift tables\. For more information, see [Multibyte Characters](c_Supported_data_types.md#c_Supported_data_types-multi-byte-characters)\. 