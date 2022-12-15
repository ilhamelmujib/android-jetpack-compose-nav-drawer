# Navigation Drawer & Effect API

Implementasikan Effect API untuk menampilkan Navigation Drawer dan Snackbar dengan aman. 

- Menggunakan scaffoldState untuk mendapatkan drawerState dan snackbarHostState.
- Menggunakan drawerState untuk membuka, menutup, dan mengetahui state Navigation Drawer.
- Menggunakan rememberCoroutineScope untuk menjalankan suspend function open() dan close() dari drawerState.
- Menggunakan Effect API seperti rememberUpdatedState, SideEffect, dan DisposableEffect untuk meng-override fungsi onBackPressed.
