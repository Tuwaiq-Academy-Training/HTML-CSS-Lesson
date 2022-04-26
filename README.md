# HTML-CSS-Lesson

# انشاء هيكل صفحة ويب باستخدام HTML


## ما هي لغة HTML؟

لغة HTML هي طريقة لكتابة وهيكلة صفحات الويب، ولاتعتبر HTML لغة برمجية بالمعنى الفعلي بل هي لغة وصفيّة، أي أنها تستخدم لوصف الصفحة وتوزيع وترتيب محتواها من نصوص وروابط وصور ومقاطع فيديو وما إلى ذلك، وهي المكون الرئيسي لأي موقع ويب، تستخدم HTML مايسمى بالوسوم أو Tags وهي عبارة عن رموز لكل منها مهمة خاصة يقوم بها، فمنها ما يقوم بعرض العنوان ومنها ما يقوم بعرض النصوص ومنها ما يقوم بعرض الصور أو الروابط أو مقاطع الفيديو وهكذا، والمتصفح يفهم هذه الرموز أو الوسوم ويعرضها بالشكل المحدد والمطلوب.


**الأجزاء الرئيسية للوسم**

- وسم‭ ‬الفتح‭ ‬أو‭ ‬البداية:

يتكون من علامتي أصغر من وأكبر من و بداخلهما اسم الوسم `<tag>`، ويحدد وسم الفتح بداية العنصر، أو بداية التأثير الذي يُضيفه.

- وسم‭ ‬الإغلاق‭ ‬أو‭ ‬النهاية:

يتكون من علامتي أصغر من وأكبر من و بداخلهما علامة مائلة `/` ثم اسم الوسم `<tag/>`. ويحدد وسم الإغلاق نهاية الوسم.

- المحتوى:

هو عبارة عن النص أو المحتوى الذي نريد عرضه أو إضافته للوسم، وتتم كتابته بين وسم الفتح ووسم الإغلاق `<tag>` المحتوى `<tag/>`.

- العنصر:

هو الكيان ككل ويشمل وسم الفتح، ووسم الإغلاق، والمحتوى.


**أنواع الوسوم**

- وسم‭ ‬عرضي:

هو عبارة عن وسم يتم عرض محتواه مباشرة على صفحة الويب.

- وسم‭ ‬وصفي:

هو عبارة عن وسم يصف مابداخله من نصوص.

# النصوص | Texts

**مقدمة في كتابة العناوين باستخدام H1 إلى H6**
للعناوين أهمية كبيرة في الصفحة سواء لفهم محتوى الصفحة أو تنظيم هيكلة الصفحة، في هذا الدرس سنتعرف على العناوين وأهميتها وعلى الأشياء التي يجب مراعاتها عند كتابة العناوين، وتستخدم الوسوم h1 إلى h6
لتحديد عناوين HTML تنازليًا من الأكثر أهمية إلى الأقل أهمية وهكذا.


**أهمية العناوين**
تأثير العناوين على المستخدم
العناوين من أهم عناصر الصفحة وهي أول ما تقع عليه العين لأن لها تأثير كبير على طريقة تصفح المستخدم للصفحة حيث يعتمد المستخدم اعتمادًا كبيرًا على العناوين أثناء تصفحه، فمن خلالها يتم فهم محتوى الصفحة وتحديد الجزء المناسب والمراد قراءته.
أهمية العناوين لهيكلة الصفحة
من المعتاد أن تكون العناوين أول العناصر التي يُبدأ فيها عند كتابة الصفحة لأن لها تأثير مباشر على هيكلة الصفحة فمن خلالها يتم فهم وتقسيم الصفحة، كما أن العناوين تلعب دورًا أساسيًا في التأثير على search engines لفهم محتوى الصفحة فهي كأهمية المعالم في الخريطة والفهرس في الكتاب سواء للمستخدم أو search engines.


**أمور يجب مراعاتها عند كتابة العناوين**
الحجم
تختلف أهمية العنوان باختلاف حجمه حيث أنه كلما ازداد حجمه ازدادت أهميته، بحيث يكون العنوان الرئيسي هو الأكبر ومن ثم العنوان الفرعي التابع للرئيسي وهكذا، بحيث لايكون العنوان الفرعي أكبر من العنوان الرئيسي الذي هو في داخله.
المعنى
العناوين تلعب دورًا أساسيًا لجذب القارئ لأنها هي المسؤولة عن وصف المحتوى فلذلك يجب أن تكون ذات معنى وسهلة الفهم بحيث تصف المحتوى وصفًا دقيقًا وكافيًا.
التسلسل
تسلسل العناوين يسهل على المستخدم فهم الصفحة بحيث تكون متسلسلة بشكل منطقي باستخدام الترتيب والحجم المناسبين.


**العناوين في html**
هناك ستة أحجام للعنوان في html بداية من h1 الأكبر وينتهي عند h6 وهو الأصغر . 
ملاحظة: لاتكتب أكثر من h1 في الصفحة.
في الأسطر التالية سيتم تغير المثال بحيث يراعي الأشياء التي يجب مراعاتها عند كتابة العناوين حيث h1 للعنوان الرئيسي و h2 للعنوان الفرعي التابع للعنوان الرئيسي وهكذا.


> ملاحظة: عند رغبتك في تكبير الخط لا تستخدم الـ tags المخصصة للعناوين بل استخدم b tags.



**مقدمة في إنشاء فقرة نصية باستخدام P**
يستخدم الوسم `<p>` لتمثيل فقرة نصية، فهو يقوم بفصل ما يكتب داخله عما قبله وبعده، ويتم ذلك بتنسيق وترتيب معين.


**طريقة استخدام** `<p>`
تتم إضافة النص المراد جعله فقرة نصية مستقلة بداخل الوسم `<p>` على الشكل الموضح في المثال التالي:

    <p>HTML stands for Hypertext Markup Language</p>

لاحظ كيف قمنا بكتابة النص داخل الوسم
والآن أصبح هذا النص عبارة عن فقرة نصية صغيرة مفصولة عما بعدها وما قبلها، وسيتم عرض هذا النص في المتصفح على النحو التالي:
HTML stands for Hypertext Markup Language
لو قمنا بكتابة هذا النص في صفحة تحتوي على نصوص أخرى فستلاحظ أن هذا النص يضيف مسافة متساوية بينه وبين جميع النصوص القريبه منه من كل الجهات


**مقدمة في مفهوم التعليقات**
التعليقات هي عبارة عن ملاحظات تتم كتابتها في المستند ويقوم المتصفح بتجاهلها وعدم عرضها، نقوم عادة بكتابة التعليقات في الملف لشرح نقطة معينة أو لوضع ملاحظة للتذكير أو التوضيح لفريق العمل، وهكذا.

**مثال**

    <!-- this is a comment -->




# تنسيق النصوص | Formatting

**مقدمة في عرض النص بخط عريض باستخدام B و Strong**
يستخدم كل من الوسم `<b>` والوسم `<strong>` لعرض النص بخط عريض، ولكل منهما دلالة مختلفة، وهذا ماسنتعرف عليه في النقاط التالية.
طريقة استخدام الوسم `<b>`
يستخدم الوسوم `<b>` لعرض النص المكتوب داخله بخط عريض، وهذا الوسم لايؤثر على أهمية أو أولوية النص في الملف، أي أن دوره تنسيقي فقط. وتتم كتابة النص أو الكلمة المراد أن تعرض بخط عريض داخل الوسم `<b>` وبالشكل الموضح في المثال التالي:

    <p>Welcome to <b>HTML</b></p>

استخدمنا الوسم `<b>` هنا لأننا نريد عرض كلمة HTML بخط عريض أي تغيير تنسيقها فقط، فهي لاتشكل معنى مهم هنا ولايوجد معنى نريد التأكيد عليه.


**طريقة استخدام الوسم**`**<strong>**`**.**
يقوم هذا الوسم بعرض النص المكتوب داخله بخط عريض، ويدل استخدامه على أن لهذا النص أهمية وتأثير، فلنفترض أننا أردنا عرض رسالة تذكير بموعد على صفحتنا، فيمكننا كتابة الرسالة بالشكل التالي:

    <p>Your appointment is on <strong>Monday</strong></p>

لاحظ كيف تمت كتابة الكلمة Mondy داخل الوسم `<strong>` وذلك لأنها أهم كلمة في الجملة وهي يوم الموعد الذي نريد تذكير المستخدم به، ظاهريًا لايوجد أي اختلاف في العرض بين الوسم `<b>` والوسم `<strong>` لكن لكل منهما معناه واستخدامه الخاص، للتنسيق فقط نستخدم الوسم `<b>` وللتنسيق والتأكيد نستخدم الوسم `<strong>`.


**مقدمة في عرض النص بخط مائل باستخدام I و Em**
يستخدم كل من الوسم `<i>` والوسم `<em>` لعرض النص بشكل مائل، ولكل منهما معنى واستخدام خاص، وهذا ماسنتعرف عليه في النقاط التالية.

**طريقة استخدام الوسم** `<i>`
تتم كتابة النص أو الكلمة المراد أن تعرض بشكل مائل داخل الوسم `<i>`، كما هو موضح في المثال التالي:

    <p>Welcome to <i>HTML</i></p>

استخدمنا الوسم `<i>` هنا لأننا نريد عرض كلمة HTML بخط مائل أي أننا نريد تغيير تنسيقها فقط.

**طريقة استخدام الوسم** `<em>`
يقوم هذا الوسم بكتابة النص المكتوب داخله بشكل مائل، ويدل استخدامه على أن لهذا النص أهمية والخط المائل هنا لغرض التأكيد أو التشديد على الكلام. يستخدم الوسم `<i>` للتنسيق فقط بينما يستخدم الوسم `<em>` للتأكيد والتشديد على أهمية النص.



**مقدمة في كتابة نص على مستوى منخفض عن السطر Sub**
يستخدم الوسم `<sub>` لتمييز نص وجعله منخفض عن السطر ومكتوب بخط أصغر، ويمكن استخدام هذا الوسم لتمثيل المعادلات الكيميائية.
طريقة استخدام `<sub>`
سنقوم في المثال التالي بتحديد جزء من النص باستخدام الوسم `<sub>` لعرضه تحت السطر أو على مستوى منخفض قليلًا عن مستوى بقية النص، ويمكننا القيام بذلك على النحو التالي:

    <p>The basic formula for water is H<sub>2</sub>0.</p>

لاحظ كيف ظهر الرقم 2 بخط أصغر وعلى مستوى منخفض عن بقية النص.


**مقدمة في كتابة نص على مستوى مرتفع عن السطر Sup**
يستخدم الوسم `<sup>` لتمييز نص وجعله مرتفع عن السطر قليلًا وبخط أصغر، ويمكن استخدام هذا الوسم لتمثيل المعادلات الرياضية.
طريقة استخدام الوسم `<sup>`
سنقوم في المثال التالي بتحديد الرقم 3 بالوسم `<sup>` لعرضه فوق السطر أو على مستوى أعلى قليلًا عن الرقم 2، ويمكننا القيام بذلك بكتابته على النحو التالي:

    <p>2<sup>3</sup></p>
    
    # القوائم | Lists


## مقدمة في list

نوع آخر شائع من العناصر النصية في HTML هو القائمة list، هناك أنواع مختلفة من القوائم، مثل قائمة غير مرتبة unordered list وقائمة مرتبة ordered list. سنلقي نظرة على كل نوع من هذه الأنواع ومتى يستخدم.


**طريقة استخدام Unordered List**
تعتبر القائمة غير المرتبة unordered list من أكثر القوائم شيوعًا، ويتم إنشاؤها باستخدام وسم ul وإنشاء عناصرها باستخدام وسم li، يوضح المثال التالي طريقة إنشاء قائمة غير مرتبة تحتفظ بثلاث ألوان:

    <ul>
     <li>red</li>
     <li>green</li>
     <li>blue</li>
    </ul>

كما ترا فإن هذه القائمة يمكن استخدامها لعرض البيانات التي لايكون ترتيبها مهم.


**طريقة استخدام Ordered List**
يمكن استخدام القائمة المرتبة ordered list عندما يكون الترتيب مهمًا، يتم إنشاؤها باستخدام وسم ol وإنشاء عناصرها باستخدام تاق li، يوضح المثال التالي طريقة إنشاء قائمة مرتبة تحتفظ بثلاث عناصر مرتبة:

    <ol>
     <li>step one</li>
     <li>step two</li>
     <li>step three</li>
    </ol>

# الروابط  | Links


## مقدمة في إضافة الروابط باستخدام Anchor

من أهم مايميز صفحات الـويب أن التنقل بين صفحاتها ليس معقد بل بغاية السهولة، وللانتقال إلى صفحة جديدة أو الانتقال إلى جزء معين على نفس الصفحة يمكن الاستعانة بوسم يعرف بالوسم `<a>` وفي هذا الدرس سنتعرف على الوسم `<a>` أهم السمات فيه وكيفية كتابته.


> ملاحظة: الأب للوسم `<a>` أي وسم باستنثاء وسم `<a>` آخر.


**الوسم** `<a>`
يستخدم الوسم `<a>` لإنشاء رابط ينتقل بنا إلى صفحات ويب، ملفات، عناوين بريد الكتروني أو أماكن أخرى بنفس الصفحة،
المفضل أن يكون محتوى الوسم `<a>` وصف موجز ذو معنى، وذلك يعود بالفائدة لمحركات البحث في معرفة المحتوى، ويمكن أن يكون محتوى الوسم `<a>` صورة او شي آخر، أي ليس مقتصر على النص. 


> ملاحظة: محتوى الوسم `<a>` هو الجزء المرئي من هذا الوسم.


**كيفية كتابة الوسم** `<a>`

    <a>
     Definition of URI and URL
    </a>

لاحظ في المثال أعلاه تم إضافة النص Definition of URI and URL كمحتوى للوسم `<a>`ولكن عند النقر عليه لن ينتقل بنا إلى أي مكان آخر وذلك بسبب عدم تحديد أهم سمة في الوسم `<a>` والتي تعرف بالسمة href.


**السمة/الخاصيّة href**
تعتبر السمة href من أهم السمات في الوسم `<a>`، قيمة هذه السمة تكون عبارة عن الصفحة أو المكان المراد الذهاب إليه عندما يقوم المستخدم بالنقر على محتوى الوسم `<a>`. يمكن أن تكون قيم السمة href:

- عنوان URL.
- عنوان بريد الكتروني باستخدام mailto.
- رقم هاتف باستخدام tel.
- وسم معين في نفس المستند باستخدام قيمة id التابعة لذلك المستند.
- لتوضيح الفكرة لاحظ معي المثال التالي:
    <a href="../reference/uri-url.html">
    
    
     Definition of URI and URL
    
    
    </a>

في المثال أعلاه قمنا بتعيين قيمة السمة `href` كعنوان URL وعند النقر على محتوى الوسم أعلاه سينتقل بنا إلى رابط الصفحة الذي تم تعيينه في السمة `href`.

> ملاحظة: إذا كان الوسم `<a>` لايحتوي على السمة `href` فلن يتم الانتقال إلى أي صفحة أو مكان عند النقر عليه.

# الجداول | Tables

**مقدمة في إنشاء الجداول باستخدام Table**
تمكنك HTML من إضافة جداول في صفحة الويب الخاصة بك، بالإضافة إلى تنظيمها وتغيير حجمها ومحتواها، تساعدك الجداول في عرض قوائم البيانات من نصوص وصور وما إلى ذلك.


**طريقة استخدام Table**
لإنشاء جدول يتم استخدام الوسم `<table>` ويتم وضع الوسم `<tr>` والوسم `<th>` والوسم `<td>` بداخله والتي تقوم بإنشاء أعمدة وصفوف الجدول.


**مثال على إنشاء جدول**
سنقوم الآن بإنشاء جدول يتكون من خانتين رئيسيتين هما Name و Age ثم سنضيف له صفين ونضيف لهما بعض البيانات

        <table>
            <tr>
                <th>Name</th>
                <th>Age</th>
            </tr>
            <tr>
                <td>Khalid</td>
                <td>19</td>
            </tr>
            <tr>
                <td>Omar</td>
                <td>17</td>
            </tr>
        </table>

# النماذج | Forms

**مقدمة في كتابة النماذج باستخدام Form**
يعتبر الوسم`<form>` من العناصر المهمة في HTML وذلك لأنه يضم بداخله عدة عناصر عن طريقها يستطيع المستخدم إرسال البيانات إلى خادم المتصفح، ببساطة يمكنك اعتبار وظيفة الوسم `<form>` تكمن في تحديد البيانات المراد إدخالها من المستخدم.


**سمات/خصائص**  `<form>`
****عند كتابة الوسم`<form>` فإن هناك بعض الخصائص المهمة التي يجب تحديد قيمها مثل السمة method والسمة action.

**خاصية** `‬method`
تقوم هذهِ الخاصية بتحديد نوع الإجراء المراد تطبيقه على البيانات التي أدخلها المستخدم وهي إرسال البيانات، يستقبل هذا الحقل نوعين من القيم وهما `get` و `post`. 
لتوضيح الفكرة لاحظ المثال التالي:

        <form method="get">
        </form>
    
        <form method="post">
        </form>


**الوسم** `<input>`
يستخدم الوسم`<input>` لتحديد حقل إدخال يقوم باستقبال البيانات المدخلة ويمكن استخدام هذا الوسم بداخل الوسم `<form>` لاستقبال بيانات المستخدم، وهو المكان الذي تقوم فيه بإدخال البيانات المراد استقبالها، يعتبر الوسم `<input>` من أهم الوسوم في `<form>` ويحتوي هذا الوسم على عدة أنواع من الحقول.


**السمة** `‭‬type`
تعتبر السمة type من أهم السمات للوسم`<input>`، فهي تقوم بتحديد نوع الحقل `<input>`،وبناءً على قيمة هذه السمة يتم تحديد شكل وطريقة العمل للوسم `<input>`. لتوضيح الفكرة سنقوم بذكر أهم القيم للسمة type بالإضافة إلى شكل وعمل القيم.


**القيمة‭`text`‭ ‬**
تعتبر القيمة `text` القيمة الابتدائية للحقل `type` فهي تمثل حقل لإدخال بيانات نصية ولتوضيح الفكرة لاحظ المثال التالي:

        <form>
        <input type="text" name="name">
        </form>


**القيمة**  `submit`  
هذه القيمة تمثل زر يقوم بإرسال أو تسليم النموذج ولتوضيح الفكرة لاحظ المثال التالي:

        <form>
        <input type="submit">
        </form>



**القيمة** `radio` 
زر انتقاء يسمح باختيار قيمة من مجموعة خيارات تجعل القيمة radio يتشكل بشكل زر الانتقاء ويسمح باختيار قيمة واحدة فقط من مجموعة خيارات ولتوضيح الفكرة لاحظ المثال التالي:

        <form>
        <p>Gender</p>
        <input type="radio" name="gender">
        <label>Female</label>
        <input type="radio" name="gender">
        <label>Male</label>
        </form>


**الوسم** `<label>`
يستخدم العنصر `<label>` لتحديد المسمى للوسم `<input>` لتوضيح الفكرة لاحظ المثال التالي:

        <form>
          <label for="fname">First name:</label>
          <input type="text" id="fname">
          <input type="submit" value="Submit">
        </form>



