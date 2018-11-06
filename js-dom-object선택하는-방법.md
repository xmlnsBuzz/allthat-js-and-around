# js-dom-object선택하는-방법

##HTML 문서에서 id 없는 body tag을 select 할 때.
>document.getElement*s*ByTagName('body')[0];

뒤에 [0]을 붙여야 만 되는 것으로 봐서 getElement로 시작하는 method는 array로 간주하는 듯 하다.
