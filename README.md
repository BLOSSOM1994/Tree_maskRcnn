# Tree_maskRcnn
<div dir="rtl">
<p>
شناسایی درخت با یادگیری عمیق</p>

<p>این ریپوزیتوری برای پایان نامه من تهیه شده است.</p>

<p>برای شروع پوشه<br />
rcnn-test *و colabnotebookssave را به درایو ریپازیتوری کولب اضاف می کنیم<br />
خط 2199 را از کدmodel.py باید تغییر داد</p>

<p>`self.keras_model.metrics_tensors.append(loss)`<br />
تغییر به<br />
`self.keras_model.add_metric(loss, name)`</p>

<p>requirements موجود راباید جایگزین requirements clone شده شود</p>

<p>فایل زیر به درایو اضافه شود</p>

<p>https://drive.google.com/file/d/1gqS6_kvf-O8EpvfLZOiZU-3bOMyolgf8/view?usp=sharing</p>
