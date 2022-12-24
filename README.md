# Tree_maskRcnn
<div dir="rtl">
شناسایی درخت با یادگیری عمیق<\br>
این ریپوزیتوری برای پایان نامه من تهیه شده است.
<div dir="rtl">
برای شروع پوشه
rcnn-test *و colabnotebookssave را به درایو ریپازیتوری کولب اضاف می کنیم
خط 2199 را از کدmodel.py باید تغییر داد

`self.keras_model.metrics_tensors.append(loss)`
تغییر به
`self.keras_model.add_metric(loss, name)`

requirements موجود راباید جایگزین requirements clone شده شود

فایل زیر به درایو اضافه شود

https://drive.google.com/file/d/1gqS6_kvf-O8EpvfLZOiZU-3bOMyolgf8/view?usp=sharing
