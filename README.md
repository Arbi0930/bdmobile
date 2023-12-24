## Онцлогууд

- **User Authentication:** Firebase Authentication ашиглан хэрэглэгчийн нэвтрэх болон бүртгэлийн аюулгүй байдал.
- **Real-time Note Management:** Тэмдэглэл үүсгэх, засах, устгах, өөрчлөлтүүдийг бодит цаг хугацаанд харуулна.
- **Sorting Notes:** Тэмдэглэлүүдийг үүсгэх цагийн тэмдгийн буурах дарааллаар харуулна.
- **Logout:** Цэс товчийг ашиглан нэг товшилтоор гарах.
- **Intuitive UI:** Тэмдэглэлийг саадгүй бичихэд зориулагдсан хэрэглэгчдэд ээлтэй интерфэйс.

 ## Files and Activities

- `CreateAccountActivity.java`: Firebase Authentication ашиглан хэрэглэгчийн бүртгэлийг зохицуулна.
- `LoginActivity.java`: Firebase Authentication ашиглан хэрэглэгчийн нэвтрэлтийг удирдана.
- `MainActivity.java`: Тэмдэглэл үзэх зориулсан програмын үндсэн дэлгэц.
- `Note.java`: Тэмдэглэлийн бүтцийг илэрхийлнэ.
- `NoteAdapter.java`: Үндсэн үйл ажиллагаанд тэмдэглэл харуулах RecyclerView адаптер.
- `NoteDetailsActivity.java`: Хэрэглэгчдэд тэмдэглэлийн дэлгэрэнгүй мэдээллийг харах, засах боломжийг олгоно.
- `SplashActivity.java`: Аппликешныг эхлүүлэх үед дэлгэцийг харуулна.
- `Utility.java`: Firebase-тай ажиллахад зориулсан туслах функцуудыг агуулна.

## Usage

- **Add a Note:** Шинэ тэмдэглэл үүсгэхийн тулд "+" товчийг дарна.
- **View/Edit a Note:** Үндсэн дэлгэц дээрх тэмдэглэл дээр товшоод агуулгыг нь харах эсвэл засах боломжтой.
- **Delete a Note:** Устгах товчийг нээхийн тулд тэмдэглэл дээр зүүн шударна уу.
- **Logout:** Гарах сонголт руу хандахын тулд цэс товчийг тов.


 ## Resources

- [Firebase Documentation](https://firebase.google.com/docs)
- [Firestore Documentation](https://firebase.google.com/docs/firestore)
- [Firebase UI for Android](https://github.com/firebase/FirebaseUI-Android)
