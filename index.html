<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Movie Web</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            background: #111;
            color: #fff;
        }

        /* Header */
        .header {
            padding: 15px 30px;
            background: #000;
            font-size: 22px;
            font-weight: bold;
            color: #e50914;
        }

        /* Banner quảng cáo */
        .banner {
            height: 70vh;
            background: linear-gradient(to top, rgba(0,0,0,0.9), rgba(0,0,0,0.2)),
            url("https://iguov8nhvyobj.vcdn.cloud/media/catalog/product/cache/1/image/1800x/71252117777b696995f01934522c402d/a/v/avatar3_teaser_poster_vietnam.jpg");
            background-size: cover;
            background-position: center;
            display: flex;
            align-items: flex-end;
            padding: 40px;
        }

        .banner-content {
            max-width: 500px;
        }

        .banner h1 {
            font-size: 40px;
            margin-bottom: 10px;
        }

        .banner p {
            font-size: 16px;
            margin-bottom: 20px;
            line-height: 1.5;
        }

        .banner button {
            padding: 10px 20px;
            border: none;
            background: #e50914;
            color: #fff;
            font-size: 16px;
            cursor: pointer;
            border-radius: 4px;
        }

        /* Movie list */
        .movie-list {
            padding: 30px;
        }

        .movie-list h2 {
            margin-bottom: 15px;
        }

        .movies {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(180px, 1fr));
            gap: 15px;
        }

        .movie {
            cursor: pointer;
            transition: transform 0.3s;
        }

        .movie:hover {
            transform: scale(1.1);
        }

        .movie img {
            width: 100%;
            border-radius: 6px;
        }

        /* Modal */
        .modal {
            display: none;
            position: fixed;
            inset: 0;
            background: rgba(0,0,0,0.9);
            justify-content: center;
            align-items: center;
            z-index: 1000;
        }

        .modal-content {
            width: 90%;
            max-width: 800px;
        }

        .close {
            color: #fff;
            font-size: 20px;
            cursor: pointer;
            float: right;
            margin-bottom: 10px;
        }

        video {
            width: 100%;
        }
        .buy-ticket {
    width: 100%;
    margin-top: 8px;
    padding: 8px;
    background: #e50914;
    border: none;
    color: white;
    font-size: 14px;
    cursor: pointer;
    border-radius: 4px;
}

.buy-ticket:hover {
    background: #ff1e26;
}
/* Modal chọn ghế */
.seat-modal {
    display: none;
    position: fixed;
    inset: 0;
    background: rgba(0,0,0,0.85);
    justify-content: center;
    align-items: center;
    z-index: 2000;
}

.seat-content {
    background: #222;
    padding: 20px;
    border-radius: 10px;
    width: 350px;
    text-align: center;
}

.seats {
    display: grid;
    grid-template-columns: repeat(5, 1fr);
    gap: 10px;
    margin: 20px 0;
}

.seat {
    padding: 12px;
    background: #444;
    border-radius: 6px;
    cursor: pointer;
}

.seat.selected {
    background: #e50914;
}

.seat-content button {
    padding: 10px 20px;
    border: none;
    background: #e50914;
    color: white;
    cursor: pointer;
    border-radius: 4px;
}
/* Modal chọn ghế */
.seat-modal {
    display: none;
    position: fixed;
    inset: 0;
    background: rgba(0,0,0,0.85);
    justify-content: center;
    align-items: center;
    z-index: 2000;
}

.seat-content {
    background: #222;
    padding: 20px;
    border-radius: 10px;
    width: 350px;
    text-align: center;
}

.seats {
    display: grid;
    grid-template-columns: repeat(5, 1fr);
    gap: 10px;
    margin: 20px 0;
}

.seat {
    padding: 12px;
    background: #444;
    border-radius: 6px;
    cursor: pointer;
}

.seat.selected {
    background: #e50914;
}

.seat-content button {
    padding: 10px 20px;
    border: none;
    background: #e50914;
    color: white;
    cursor: pointer;
    border-radius: 4px;
}
/* Khu vực màn hình */
.screen {
    background: #ccc;
    height: 20px;
    width: 100%;
    margin: 10px 0 20px;
    border-radius: 4px;
    text-align: center;
    color: #000;
    font-size: 12px;
    line-height: 20px;
}

/* Sơ đồ ghế */
.seats {
    display: flex;
    flex-direction: column;
    gap: 10px;
}

.row {
    display: flex;
    justify-content: center;
    gap: 8px;
}

.seat {
    width: 35px;
    height: 35px;
    background: #444;
    border-radius: 6px;
    cursor: pointer;
    font-size: 12px;
    line-height: 35px;
}

.seat.selected {
    background: #e50914;
}

.seat.occupied {
    background: #777;
    cursor: not-allowed;
}

/* Lối đi */
.aisle {
    width: 20px;
}


    </style>
</head>

<body>

<select id="ticketType" onchange="calcTotal()">
    <option value="80000">🎟 Vé thường - 80.000 VNĐ</option>

    <option value="120000">⭐ Vé VIP - 120.000 VNĐ</option>
</select>
<label>
    <input type="checkbox" id="combo" onchange="calcTotal()">
    🍿 Combo bắp + nước 
</label>
<br></br>
<p>
    Tổng tiền: <strong id="total">130000</strong> VNĐ
</p>




<div class="header">🎬 MovieFlix</div>

<!-- Banner quảng cáo phim -->
<div class="banner">
    <div class="banner-content">
        <h1>AVATAR 3</h1>
        <p>KHỞI CHIẾU TẠI RẠP 19.12.2025</p>
    </div>
</div>

<!-- Danh sách phim -->
<div class="movie">
    <h2>Phim đang chiếu</h2>
    <div class="movies" id="movieList"></div>
</div>
<div class="movie-list">
    <h2>Phim Sắp chiếu</h2>
    <div class="movies" id="movieList"></div>
<div class="movie-list">
    <h2> Vé đã thanh toán</h2>
  <ul id="history"></ul>
</div>

<script>
    const movies = [
        {
            
            title: "VI PHỤ ĐỘNG TRỜI",
            poster: "https://iguov8nhvyobj.vcdn.cloud/media/catalog/product/cache/1/image/c5f0a1eff4c394a251036189ccddaacd/c/g/cgv_350x495_1_1.jpg",
            price: 120000
    
        },
        {
            title: "VUA CỦA CÁC VUA",
            poster: "https://iguov8nhvyobj.vcdn.cloud/media/catalog/product/cache/1/image/c5f0a1eff4c394a251036189ccddaacd/1/8/18._470x700-king.jpg",
            price: 80000
        },
        {
            title: "THẾ HỆ KỲ TÍCH (BÀ CON ĐỪNG BUỒN)",
            poster: "https://iguov8nhvyobj.vcdn.cloud/media/catalog/product/cache/1/image/c5f0a1eff4c394a251036189ccddaacd/m/a/main_thkt_cinema.jpg",
            price: 90000
        },
        {
            title: "AVARTA3",
            poster: "https://upload.wikimedia.org/wikipedia/vi/5/58/Avatar_3_teaser.jpg",
            price: 80000
        },
         {
            title: "HÀNG XÓM CỦA TÔI LÀ TOTORO",
            poster: "https://iguov8nhvyobj.vcdn.cloud/media/catalog/product/cache/1/image/1800x/71252117777b696995f01934522c402d/o/l/ol_localize_totoroposter_251118.jpg",
            price: 98000
            
        },
         {
            title: "PHIM ĐIỆN ẢNH LUPIN ĐỆ TAM: LÂU ĐÀI CAGLIOSTRO",
            poster: "https://iguov8nhvyobj.vcdn.cloud/media/catalog/product/cache/1/image/c5f0a1eff4c394a251036189ccddaacd/p/o/poster_lupin3rd_localize.jpg",
            price: 80000
        },
         {
            title: "PHIM HẬU DUỆ CHỨC NỮ ",
            poster: "https://iguov8nhvyobj.vcdn.cloud/media/catalog/product/cache/1/image/c5f0a1eff4c394a251036189ccddaacd/l/p/lpt_poster-5_3d.jpg",
            price: 120000
        },
   
                 {
            title: "PHIM 5 CENTIMET TRÊN GIÂY ",
            poster: "https://upload.wikimedia.org/wikipedia/vi/thumb/b/b7/5_centimet_tr%C3%AAn_gi%C3%A2y.jpg/330px-5_centimet_tr%C3%AAn_gi%C3%A2y.jpg",
            price: 80000
        },
   
   
   
   
    ];

   const movieList = document.getElementById("movieList");

movies.forEach(movie => {
    const div = document.createElement("div");
    div.className = "movie";

    div.innerHTML = `
        <img src="${movie.poster}">
        <p>${movie.title}</p>
        <p> ${movie.price.toLocaleString()} VNĐ</p>
        <button class="buy-ticket">ĐẶT VÉ</button>
    `;

    div.querySelector(".buy-ticket").onclick = () => buyTicket(movie);

    movieList.appendChild(div);
});

    function openMovie(video) {
        movieVideo.src = video;
        modal.style.display = "flex";
    }

    function closeMovie() {
        modal.style.display = "none";
        movieVideo.pause();
    }

    function playBanner() {
        openMovie("https://www.w3schools.com/html/mov_bbb.mp4");
    }
  function buyTicket(movie) {
    const history =
        JSON.parse(localStorage.getItem("ticketHistory")) || [];

    history.push({
        title: movie.title,
        price: movie.price,
        time: new Date().toLocaleString()
    });

    localStorage.setItem("ticketHistory", JSON.stringify(history));

    renderHistory();
    
    alert("🎉 Mua vé thành công!");
    "Phim: " + movie.title + "\n" +
        "Giá vé: " + ticketPrice.toLocaleString() + " VNĐ"
}

let selectedSeat = null;

function openSeatModal(movieTitle) {
    document.getElementById("movieName").innerText =
        "🎬 " + movieTitle;

    const seatList = document.getElementById("seatList");
    seatList.innerHTML = "";
    selectedSeat = null;

    const rows = ["A", "B", "C", "D", "E", "G", "F"];

    rows.forEach(rowName => {
        const row = document.createElement("div");
        row.className = "row";

        for (let i = 1; i <= 8; i++) {
            if (i === 5) {
                const aisle = document.createElement("div");
                aisle.className = "aisle";
                row.appendChild(aisle);
            }

            const seat = document.createElement("div");
            seat.className = "seat";
            seat.innerText = rowName + i;

            seat.onclick = () => {
                if (seat.classList.contains("occupied")) return;

                document.querySelectorAll(".seat").forEach(s =>
                    s.classList.remove("selected")
                );

                seat.classList.add("selected");
                selectedSeat = seat.innerText;
            };

            row.appendChild(seat);
        }

        seatList.appendChild(row);
    });

    document.getElementById("seatModal").style.display = "flex";
}

function confirmSeat() {
    if (!selectedSeat) {
        alert("⚠️ Vui lòng chọn ghế!");
        return;
    }

    alert("✅ Bạn đã đặt ghế " + selectedSeat + " thành công!");
    closeSeatModal();
}

function closeSeatModal() {
    document.getElementById("seatModal").style.display = "none";
}


function confirmSeat() {
    if (!selectedSeat) {
        alert("⚠️ Vui lòng chọn ghế!");
        return;
    }

   alert(
        "🎉 Đặt vé thành công!\n" +
        "Ghế: " + selectedSeat + "\n" +
        "Giá vé: 89.000 VNĐ"
    );

    closeSeatModal();
}
function calcTotal() {
    let ticketPrice = Number(document.getElementById("ticketType").value);
    let combo = document.getElementById("combo").checked;

    let total = ticketPrice;

    if (combo) {
        total += 50000;
    }

    document.getElementById("total").innerText =
        total.toLocaleString();
}
function renderHistory() {
    const history =
        JSON.parse(localStorage.getItem("ticketHistory")) || [];

    const list = document.getElementById("history");
    list.innerHTML = "";

    history.forEach(item => {
        const li = document.createElement("li");
        li.innerText =
            `🎬 ${item.title} - ${item.price.toLocaleString()} VNĐ (${item.time})`;
        list.appendChild(li);
    });
}

// Load lịch sử khi mở trang
renderHistory();

</script>
<div class="seat-modal" id="seatModal">
    <div class="seat-content">
        <h3 id="movieName">Chọn ghế</h3>
<p>
    Ghế đã chọn: <strong id="chosenSeat">---</strong><br>
    Giá vé: <strong id="price">89.000</strong> VNĐ
</p>

        <div class="seats" id="seatList"></div>

        <button onclick="confirmSeat()">Xác nhận</button>
        <br><br>
        <span class="close" onclick="closeSeatModal()">❌ Đóng</span>
    </div>
</div>

</body>
</html>
