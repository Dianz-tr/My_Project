#My_Project
Repository Baru di lokal

# Sebuah Komentar akan diabaikan  
*.env #abaikan semua file dengan akhiran .env
!lib.env # tetapi lakukan track pada lib.env, jika telah mengabaikan file .env
/TODO  # hanya abaikan semua file yang ada di dalam TODO, tetapi tidak dengan  subdirektori / TODO
build/    # abaikan semua file didalam direktori build/ termasuk didalam subdirektorinya 
doc/*.txt  # abaikan doc/notes.txt, tetapi tidak dengan doc/server/arch.txt