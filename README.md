# SafeTensors_Image_Generatio_Models
**შესავალი**

ამ რეპოზიტორში გთავაზობთ დეტალურ და პროფესიონალურ აღწერას **SafeTensors**-ის მოდელებისთვის, რომლებიც შექმნილია სურათების გენერაციაში მაღალი ზუსტობისთვის. აქ შეტანილია იმ მოდელების მიმოხილვა, რომლებიც განახლებულია და განვრცობილია **ადაპტაციის**, **სეგმენტაციის**, **ფერების მართვის**, **ედჟების** და სხვა მნიშვნელოვანი ფუნქციების დასახელებასთან ერთად.

# მოდელების აღწერა

**1. control_canny-fp16.safetensors**

გენერირება **Canny** კონტურთა მოდელისთვის, რომელიც ეფუძნება სურათებზე ედჟების აღმოჩენას.

**2. control_depth-fp16.safetensors**

სიღრმის მაპების გენერაციის მოდელი, რომელიც საჭიროა **3D** სურათის გენერირებისთვის.

**3. control_hed-fp16.safetensors**

ედჟების მთლიანი დეტექციის **(Holistic Edge Detection)** მოდელი.

**4. control_mlsd-fp16.safetensors**

მართვის და აღმოჩენის ფუნქცია სურათებზე, სინათლის და მინიმულისტური შტრიხებისთვის.

**5. control_normal-fp16.safetensors**

სურათების ნორმალური მაპების გენერაცია, რაც აჩვენებს ფიზიკურ დეტალებს.

6. **control_openpose-fp16.safetensors**

პოზიციების და მოძრაობის დეტექციის მოდელი სურათებზე.

**7. control_scribble-fp16.safetensors**

მარტივი სკრიბლების და ნახაზების გენერაცია სურათებზე.

**8. control_seg-fp16.safetensors**

სეგმენტაციის მოდელი, სურათების დაყოფა რეგიონებად.

**9. tziadapter_canny-fp16.safetensors**

**Canny** კონტურების ადაპტირება სპეციფიურ სურათებზე.

**10. tziadapter_color-fp16.safetensors**

სურათების ფერების ადაპტირება გენერაციისთვის.

**11. tziadapter_depth-fp16.safetensors**

სიღრმის მაპების ადაპტირება გენერაციისთვის.

**12. tziadapter_keypose-fp16.safetensors**

პოზიციების და გესტულაციების ადაპტირება სურათებზე.

**13. tziadapter_openpose-fp16.safetensors**

**OpenPose** მოდელის ადაპტირება, პოზიციების აღმოჩენა.

**14. tziadapter_seg-fp16.safetensors**

სეგმენტაციის მოდელის ადაპტირება, რათა მოხდეს სურათების დაყოფა რეგიონებად.

**15. tziadapter_sketch-fp16.safetensors**

ნახაზების და სკრიბლების ადაპტირება.

**16. tziadapter_style-fp16.safetensors**

სტილების ადაპტირება გენერაციისთვის.

# დასკვნა

სურათთა გენერაციის ზუსტობის მაღალი დონეზე დასაყენებელი მოდელების გამოყენება რეპოზიტორში ადაპტირებს და კონტროლირებს სურათების გენერაციას, რათა გამოიყენოს სპეციფიურ პროექტებში და გააჩნდეს მაღალი სიზუსტე და დეტალურობა. ეს მოდელები შეიცავს **ედჟების დეტექციას**, **სიღრმის გენერაციას**, **ფერების მართვას**, **პოზიციების დეტექციას** და სხვას.

