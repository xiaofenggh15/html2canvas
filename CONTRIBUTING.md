I want to change line 132 in cache-storage.ts from 
            const responseType = FEATURES.SUPPORT_RESPONSE_TYPE ? 'blob' : 'text';
to 
            const responseType = FEATURES.SUPPORT_RESPONSE_TYPE ? 'text' : 'blob';
The reason is stated as in issue reported in https://github.com/niklasvh/html2canvas/issues/2753. Let me know if you think this change makes sense or not. Thanks!
