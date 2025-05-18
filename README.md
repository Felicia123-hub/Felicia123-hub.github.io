<!DOCTYPE html>
<html lang="vi">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Chất lượng giấc ngủ của Học sinh THPT</title>
    <script src="https://cdn.tailwindcss.com/3.4.16"></script>
    <script>
      tailwind.config = {
        theme: {
          extend: {
            colors: {
              primary: "#1B2B4B",
              secondary: "#6B4E71",
              lightblue: "#A9C7E5",
            },
            borderRadius: {
              none: "0px",
              sm: "4px",
              DEFAULT: "8px",
              md: "12px",
              lg: "16px",
              xl: "20px",
              "2xl": "24px",
              "3xl": "32px",
              full: "9999px",
              button: "8px",
            },
          },
        },
      };
    </script>
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Pacifico&display=swap"
      rel="stylesheet"
    />
    <link
      href="https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;500;600;700&display=swap"
      rel="stylesheet"
    />
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/remixicon/4.6.0/remixicon.min.css"
    />
    <style>
      :where([class^="ri-"])::before { content: "\f3c2"; }
      body {
      font-family: 'Montserrat', sans-serif;
      color: #333;
      }
      .hero-section {
      background-image: linear-gradient(rgba(27, 43, 75, 0.7), rgba(27, 43, 75, 0.7)), url('https://readdy.ai/api/search-image?query=Beautiful%20night%20sky%20with%20stars%20and%20moon%20over%20a%20peaceful%20landscape%2C%20dark%20blue%20gradient%2C%20calming%20atmosphere%2C%20high%20quality%20digital%20art%20with%20smooth%20transitions%2C%20perfect%20for%20website%20background&width=1920&height=800&seq=1&orientation=landscape');
      background-size: cover;
      background-position: center;
      }
      .card-hover:hover {
      transform: translateY(-5px);
      box-shadow: 0 10px 20px rgba(0,0,0,0.1);
      }
      .counter-banner {
      background-image: linear-gradient(to right, rgba(27, 43, 75, 0.9), rgba(107, 78, 113, 0.9)), url('https://readdy.ai/api/search-image?query=Abstract%20pattern%20of%20stars%20and%20moon%20phases%20on%20dark%20blue%20background%2C%20subtle%20and%20elegant%20design%20for%20website%20banner%2C%20digital%20illustration%20with%20smooth%20gradients&width=1200&height=200&seq=2&orientation=landscape');
      background-size: cover;
      background-position: center;
      }
      input[type="number"]::-webkit-inner-spin-button,
      input[type="number"]::-webkit-outer-spin-button {
      -webkit-appearance: none;
      margin: 0;
      }
      .article-card {
      transition: all 0.3s ease;
      }
      .article-card:hover {
      transform: translateY(-5px);
      }
      .nav-link {
      position: relative;
      }
      .nav-link::after {
      content: '';
      position: absolute;
      width: 0;
      height: 2px;
      bottom: -2px;
      left: 0;
      background-color: #A9C7E5;
      transition: width 0.3s ease;
      }
      .nav-link:hover::after, .nav-link.active::after {
      width: 100%;
      }
    </style>
  </head>
  <body class="bg-white">
    <!-- Header Navigation -->
    <header class="bg-primary text-white shadow-md">
      <div class="container mx-auto px-4 py-3">
        <div class="flex justify-between items-center">
          <div class="flex items-center">
            <div class="w-10 h-10 flex items-center justify-center mr-2">
              <i class="ri-moon-fill ri-2x text-lightblue"></i>
            </div>
            <h1 class="text-xl font-['Pacifico'] text-lightblue">SleepWell</h1>
          </div>
          <nav class="hidden md:flex space-x-8">
            <a
              href="#"
              class="nav-link active py-2 text-white hover:text-lightblue transition duration-300"
              >Trang chủ</a
            >
            <a
              href="https://readdy.ai/home/b380f0ce-552a-48af-8418-8add9b7b518e/b647c132-8871-406d-9329-69d0a76ddbb6"
              data-readdy="true"
              class="nav-link py-2 text-white hover:text-lightblue transition duration-300"
              >Đánh giá Giấc ngủ</a
            >
            <a
              href="#"
              class="nav-link py-2 text-white hover:text-lightblue transition duration-300"
              >Tư vấn AI</a
            >
          </nav>
          <div class="md:hidden w-8 h-8 flex items-center justify-center">
            <i class="ri-menu-line ri-2x text-white"></i>
          </div>
        </div>
      </div>
    </header>
    <!-- Main Content -->
    <main>
      <!-- Hero Section -->
      <section class="hero-section text-white">
        <div class="container mx-auto px-4 py-20">
          <div class="w-full max-w-3xl">
            <h1 class="text-4xl md:text-5xl font-bold mb-6">
              Chất lượng giấc ngủ của Học sinh THPT
            </h1>
            <p class="text-xl mb-8">
              Hiểu và cải thiện giấc ngủ để nâng cao sức khỏe và kết quả học tập
            </p>
            <div class="flex flex-col sm:flex-row gap-4">
              <button
                class="bg-lightblue text-primary font-semibold px-6 py-3 !rounded-button whitespace-nowrap hover:bg-opacity-90 transition duration-300"
              >
                Đánh giá giấc ngủ
              </button>
              <a
                href="https://readdy.ai/home/b380f0ce-552a-48af-8418-8add9b7b518e/86c36eed-9c56-43e0-a819-863d32f89c55"
                data-readdy="true"
                class="bg-transparent border-2 border-white text-white font-semibold px-6 py-3 !rounded-button whitespace-nowrap hover:bg-white hover:bg-opacity-10 transition duration-300"
                >Tìm hiểu thêm</a
              >
            </div>
          </div>
        </div>
      </section>
      <!-- Counter Banner -->
      <section class="counter-banner text-white py-6">
        <div class="container mx-auto px-4">
          <div class="flex flex-col md:flex-row justify-between items-center">
            <div class="mb-4 md:mb-0">
              <h2 class="text-2xl font-semibold">Cộng đồng của chúng tôi</h2>
              <p>Cùng nhau hướng tới giấc ngủ chất lượng hơn</p>
            </div>
            <div class="flex space-x-8">
              <div class="text-center">
                <div class="text-3xl font-bold" id="visitor-count">12,458</div>
                <div class="text-sm">Lượt truy cập</div>
              </div>
              <div class="text-center">
                <div class="text-3xl font-bold" id="assessment-count">
                  8,721
                </div>
                <div class="text-sm">Đánh giá</div>
              </div>
              <div class="text-center">
                <div class="text-3xl font-bold" id="consultation-count">
                  5,392
                </div>
                <div class="text-sm">Lượt tư vấn</div>
              </div>
            </div>
          </div>
        </div>
      </section>
      <!-- Introduction Section -->
      <section class="py-16 bg-gray-50">
        <div class="container mx-auto px-4">
          <div class="text-center mb-12">
            <h2 class="text-3xl font-bold text-primary mb-4">
              Chất lượng giấc ngủ là gì?
            </h2>
            <p class="max-w-3xl mx-auto text-gray-600">
              Hiểu rõ về giấc ngủ là bước đầu tiên để cải thiện sức khỏe và hiệu
              suất học tập của học sinh
            </p>
          </div>
          <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            <div
              class="bg-white p-6 rounded shadow-md card-hover transition-all duration-300"
            >
              <div
                class="w-12 h-12 flex items-center justify-center mb-4 bg-lightblue bg-opacity-20 rounded-full"
              >
                <i class="ri-time-line ri-xl text-primary"></i>
              </div>
              <h3 class="text-xl font-semibold mb-3 text-primary">
                Thời lượng giấc ngủ
              </h3>
              <p class="text-gray-600">
                Học sinh THPT cần ngủ từ 8-10 giờ mỗi đêm để đảm bảo sự phát
                triển não bộ và sức khỏe tổng thể. Thiếu ngủ kéo dài có thể ảnh
                hưởng nghiêm trọng đến khả năng học tập và tâm lý.
              </p>
            </div>
            <div
              class="bg-white p-6 rounded shadow-md card-hover transition-all duration-300"
            >
              <div
                class="w-12 h-12 flex items-center justify-center mb-4 bg-lightblue bg-opacity-20 rounded-full"
              >
                <i class="ri-moon-clear-line ri-xl text-primary"></i>
              </div>
              <h3 class="text-xl font-semibold mb-3 text-primary">
                Chất lượng giấc ngủ
              </h3>
              <p class="text-gray-600">
                Không chỉ là thời gian ngủ, mà còn là khả năng đi vào giấc ngủ
                sâu và trải qua đủ các chu kỳ ngủ REM. Giấc ngủ chất lượng giúp
                củng cố trí nhớ và tăng cường khả năng tập trung.
              </p>
            </div>
            <div
              class="bg-white p-6 rounded shadow-md card-hover transition-all duration-300"
            >
              <div
                class="w-12 h-12 flex items-center justify-center mb-4 bg-lightblue bg-opacity-20 rounded-full"
              >
                <i class="ri-rhythm-line ri-xl text-primary"></i>
              </div>
              <h3 class="text-xl font-semibold mb-3 text-primary">
                Nhịp sinh học
              </h3>
              <p class="text-gray-600">
                Duy trì lịch trình ngủ đều đặn giúp cơ thể điều chỉnh nhịp sinh
                học tự nhiên. Việc đi ngủ và thức dậy cùng một thời điểm mỗi
                ngày cải thiện đáng kể chất lượng giấc ngủ.
              </p>
            </div>
          </div>
          <div class="mt-16 bg-white p-8 rounded-lg shadow-lg">
            <div class="flex flex-col md:flex-row items-center">
              <div class="md:w-1/2 mb-6 md:mb-0 md:pr-8">
                <img
                  src="https://readdy.ai/api/search-image?query=Sleep%20cycle%20infographic%20showing%20different%20sleep%20stages%20with%20brain%20waves%20patterns%2C%20REM%20sleep%2C%20deep%20sleep%2C%20and%20light%20sleep%20phases%2C%20educational%20illustration%20with%20blue%20color%20scheme%2C%20clean%20design%20for%20health%20education&width=600&height=400&seq=3&orientation=landscape"
                  alt="Chu kỳ giấc ngủ"
                  class="rounded-lg w-full h-auto object-cover"
                />
              </div>
              <div class="md:w-1/2">
                <h3 class="text-2xl font-semibold mb-4 text-primary">
                  Chu kỳ giấc ngủ của học sinh
                </h3>
                <p class="text-gray-600 mb-4">
                  Giấc ngủ của con người gồm nhiều chu kỳ, mỗi chu kỳ kéo dài
                  khoảng 90 phút và bao gồm các giai đoạn ngủ khác nhau:
                </p>
                <ul class="space-y-2 text-gray-600">
                  <li class="flex items-start">
                    <div
                      class="w-5 h-5 flex items-center justify-center mt-1 mr-2 text-lightblue"
                    >
                      <i class="ri-checkbox-circle-line"></i>
                    </div>
                    <span
                      ><strong>Giai đoạn 1 (N1):</strong> Ngủ nhẹ, dễ bị đánh
                      thức</span
                    >
                  </li>
                  <li class="flex items-start">
                    <div
                      class="w-5 h-5 flex items-center justify-center mt-1 mr-2 text-lightblue"
                    >
                      <i class="ri-checkbox-circle-line"></i>
                    </div>
                    <span
                      ><strong>Giai đoạn 2 (N2):</strong> Ngủ nhẹ hơn, nhiệt độ
                      cơ thể giảm, nhịp tim chậm lại</span
                    >
                  </li>
                  <li class="flex items-start">
                    <div
                      class="w-5 h-5 flex items-center justify-center mt-1 mr-2 text-lightblue"
                    >
                      <i class="ri-checkbox-circle-line"></i>
                    </div>
                    <span
                      ><strong>Giai đoạn 3 (N3):</strong> Ngủ sâu, rất khó đánh
                      thức, cơ thể phục hồi</span
                    >
                  </li>
                  <li class="flex items-start">
                    <div
                      class="w-5 h-5 flex items-center justify-center mt-1 mr-2 text-lightblue"
                    >
                      <i class="ri-checkbox-circle-line"></i>
                    </div>
                    <span
                      ><strong>Giai đoạn REM:</strong> Mắt chuyển động nhanh, mơ
                      nhiều, não hoạt động mạnh</span
                    >
                  </li>
                </ul>
                <p class="mt-4 text-gray-600">
                  Học sinh cần trải qua đủ các chu kỳ này để đảm bảo não bộ và
                  cơ thể được phục hồi hoàn toàn.
                </p>
              </div>
            </div>
          </div>
        </div>
      </section>
      <!-- Articles Section -->
      <section class="py-16">
        <div class="container mx-auto px-4">
          <div class="text-center mb-12">
            <h2 class="text-3xl font-bold text-primary mb-4">
              Cải thiện giấc ngủ của bạn
            </h2>
            <p class="max-w-3xl mx-auto text-gray-600">
              Những bài viết hữu ích giúp học sinh THPT có được giấc ngủ chất
              lượng hơn
            </p>
          </div>
          <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            <div
              class="article-card bg-white rounded-lg overflow-hidden shadow-md"
            >
              <img
                src="https://readdy.ai/api/search-image?query=Peaceful%20bedroom%20with%20soft%20blue%20lighting%2C%20cozy%20bed%20with%20comfortable%20pillows%20and%20blankets%2C%20minimalist%20design%2C%20calm%20atmosphere%20for%20good%20sleep%2C%20high%20quality%20digital%20art&width=400&height=250&seq=4&orientation=landscape"
                alt="Môi trường ngủ lý tưởng"
                class="w-full h-48 object-cover object-top"
              />
              <div class="p-6">
                <h3 class="text-xl font-semibold mb-3 text-primary">
                  Tạo môi trường ngủ lý tưởng
                </h3>
                <p class="text-gray-600 mb-4">
                  Khám phá cách thiết kế không gian ngủ tối ưu với nhiệt độ, ánh
                  sáng và độ ồn phù hợp để có giấc ngủ sâu hơn.
                </p>
                <div class="flex justify-between items-center">
                  <span class="text-sm text-gray-500">10 phút đọc</span>
                  <button
                    class="text-primary font-medium flex items-center !rounded-button whitespace-nowrap"
                  >
                    Đọc thêm
                    <div class="w-5 h-5 flex items-center justify-center ml-1">
                      <i class="ri-arrow-right-line"></i>
                    </div>
                  </button>
                </div>
              </div>
            </div>
            <div
              class="article-card bg-white rounded-lg overflow-hidden shadow-md"
            >
              <img
                src="https://readdy.ai/api/search-image?query=Student%20studying%20late%20at%20night%20with%20digital%20devices%2C%20blue%20light%20from%20screens%2C%20tired%20expression%2C%20contrasted%20with%20a%20peaceful%20sleeping%20scene%2C%20educational%20illustration%20about%20screen%20time%20effects%20on%20sleep&width=400&height=250&seq=5&orientation=landscape"
                alt="Tác động của thiết bị điện tử"
                class="w-full h-48 object-cover object-top"
              />
              <div class="p-6">
                <h3 class="text-xl font-semibold mb-3 text-primary">
                  Thiết bị điện tử và giấc ngủ
                </h3>
                <p class="text-gray-600 mb-4">
                  Ánh sáng xanh từ điện thoại, máy tính có thể ảnh hưởng nghiêm
                  trọng đến chất lượng giấc ngủ của học sinh như thế nào?
                </p>
                <div class="flex justify-between items-center">
                  <span class="text-sm text-gray-500">8 phút đọc</span>
                  <button
                    class="text-primary font-medium flex items-center !rounded-button whitespace-nowrap"
                  >
                    Đọc thêm
                    <div class="w-5 h-5 flex items-center justify-center ml-1">
                      <i class="ri-arrow-right-line"></i>
                    </div>
                  </button>
                </div>
              </div>
            </div>
            <div
              class="article-card bg-white rounded-lg overflow-hidden shadow-md"
            >
              <img
                src="https://readdy.ai/api/search-image?query=Student%20with%20organized%20schedule%20planner%20showing%20study%20time%2C%20relaxation%2C%20and%20sleep%20hours%2C%20balanced%20lifestyle%20illustration%2C%20time%20management%20concept%20for%20high%20school%20students%2C%20digital%20art%20with%20blue%20color%20scheme&width=400&height=250&seq=6&orientation=landscape"
                alt="Lịch trình học tập và ngủ"
                class="w-full h-48 object-cover object-top"
              />
              <div class="p-6">
                <h3 class="text-xl font-semibold mb-3 text-primary">
                  Cân bằng học tập và nghỉ ngơi
                </h3>
                <p class="text-gray-600 mb-4">
                  Chiến lược quản lý thời gian hiệu quả giúp học sinh THPT vừa
                  đạt kết quả học tập tốt vừa đảm bảo đủ giấc ngủ cần thiết.
                </p>
                <div class="flex justify-between items-center">
                  <span class="text-sm text-gray-500">12 phút đọc</span>
                  <button
                    class="text-primary font-medium flex items-center !rounded-button whitespace-nowrap"
                  >
                    Đọc thêm
                    <div class="w-5 h-5 flex items-center justify-center ml-1">
                      <i class="ri-arrow-right-line"></i>
                    </div>
                  </button>
                </div>
              </div>
            </div>
          </div>
          <div class="mt-12 text-center">
            <button
              class="bg-primary text-white font-semibold px-6 py-3 !rounded-button whitespace-nowrap hover:bg-opacity-90 transition duration-300 flex items-center mx-auto"
            >
              Xem tất cả bài viết
              <div class="w-5 h-5 flex items-center justify-center ml-2">
                <i class="ri-arrow-right-line"></i>
              </div>
            </button>
          </div>
        </div>
      </section>
      <!-- Features Section -->
      <section class="py-16 bg-gray-50">
        <div class="container mx-auto px-4">
          <div class="text-center mb-12">
            <h2 class="text-3xl font-bold text-primary mb-4">
              Các tính năng của chúng tôi
            </h2>
            <p class="max-w-3xl mx-auto text-gray-600">
              Khám phá các công cụ giúp học sinh THPT hiểu và cải thiện chất
              lượng giấc ngủ
            </p>
          </div>
          <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
            <div
              class="bg-white p-8 rounded-lg shadow-md flex flex-col md:flex-row items-center"
            >
              <div class="md:w-1/3 mb-6 md:mb-0">
                <img
                  src="https://readdy.ai/api/search-image?query=Sleep%20quality%20assessment%20chart%20with%20stars%20rating%20system%2C%20professional%20looking%20medical%20questionnaire%20design%2C%20sleep%20tracking%20visualization%2C%20clean%20modern%20interface%20with%20blue%20and%20purple%20colors&width=300&height=300&seq=7&orientation=squarish"
                  alt="Đánh giá giấc ngủ"
                  class="w-full h-auto rounded"
                />
              </div>
              <div class="md:w-2/3 md:pl-8">
                <h3 class="text-2xl font-semibold mb-3 text-primary">
                  Đánh giá chất lượng giấc ngủ
                </h3>
                <p class="text-gray-600 mb-4">
                  Bộ công cụ đánh giá toàn diện dựa trên các tiêu chuẩn khoa
                  học, giúp học sinh hiểu rõ tình trạng giấc ngủ hiện tại của
                  mình.
                </p>
                <ul class="space-y-2 text-gray-600 mb-6">
                  <li class="flex items-start">
                    <div
                      class="w-5 h-5 flex items-center justify-center mt-1 mr-2 text-lightblue"
                    >
                      <i class="ri-check-line"></i>
                    </div>
                    <span>Bảng câu hỏi đánh giá khoa học</span>
                  </li>
                  <li class="flex items-start">
                    <div
                      class="w-5 h-5 flex items-center justify-center mt-1 mr-2 text-lightblue"
                    >
                      <i class="ri-check-line"></i>
                    </div>
                    <span>Phân tích chi tiết từng khía cạnh giấc ngủ</span>
                  </li>
                  <li class="flex items-start">
                    <div
                      class="w-5 h-5 flex items-center justify-center mt-1 mr-2 text-lightblue"
                    >
                      <i class="ri-check-line"></i>
                    </div>
                    <span>So sánh với dữ liệu của học sinh cùng độ tuổi</span>
                  </li>
                </ul>
                <button
                  class="bg-primary text-white font-semibold px-6 py-3 !rounded-button whitespace-nowrap hover:bg-opacity-90 transition duration-300"
                >
                  Đánh giá ngay
                </button>
              </div>
            </div>
            <div
              class="bg-white p-8 rounded-lg shadow-md flex flex-col md:flex-row items-center"
            >
              <div class="md:w-1/3 mb-6 md:mb-0">
                <img
                  src="https://readdy.ai/api/search-image?query=AI%20chatbot%20interface%20helping%20with%20sleep%20schedule%2C%20digital%20assistant%20with%20calendar%20and%20time%20management%20tools%2C%20modern%20UI%20design%20with%20purple%20and%20blue%20color%20scheme%2C%20clean%20professional%20look&width=300&height=300&seq=8&orientation=squarish"
                  alt="Tư vấn AI"
                  class="w-full h-auto rounded"
                />
              </div>
              <div class="md:w-2/3 md:pl-8">
                <h3 class="text-2xl font-semibold mb-3 text-primary">
                  Tư vấn AI quản lý thời gian
                </h3>
                <p class="text-gray-600 mb-4">
                  Trợ lý AI thông minh giúp học sinh lập kế hoạch học tập và
                  nghỉ ngơi hợp lý, đảm bảo đủ 7-8 giờ ngủ mỗi đêm.
                </p>
                <ul class="space-y-2 text-gray-600 mb-6">
                  <li class="flex items-start">
                    <div
                      class="w-5 h-5 flex items-center justify-center mt-1 mr-2 text-lightblue"
                    >
                      <i class="ri-check-line"></i>
                    </div>
                    <span>Tư vấn cá nhân hóa theo lịch học</span>
                  </li>
                  <li class="flex items-start">
                    <div
                      class="w-5 h-5 flex items-center justify-center mt-1 mr-2 text-lightblue"
                    >
                      <i class="ri-check-line"></i>
                    </div>
                    <span>Gợi ý thời gian học tập hiệu quả</span>
                  </li>
                  <li class="flex items-start">
                    <div
                      class="w-5 h-5 flex items-center justify-center mt-1 mr-2 text-lightblue"
                    >
                      <i class="ri-check-line"></i>
                    </div>
                    <span>Nhắc nhở lịch ngủ và thức dậy đều đặn</span>
                  </li>
                </ul>
                <button
                  class="bg-primary text-white font-semibold px-6 py-3 !rounded-button whitespace-nowrap hover:bg-opacity-90 transition duration-300"
                >
                  Trò chuyện với AI
                </button>
              </div>
            </div>
          </div>
        </div>
      </section>
      <!-- Testimonials -->
      <section class="py-16">
        <div class="container mx-auto px-4">
          <div class="text-center mb-12">
            <h2 class="text-3xl font-bold text-primary mb-4">
              Chia sẻ từ học sinh
            </h2>
            <p class="max-w-3xl mx-auto text-gray-600">
              Những trải nghiệm thực tế từ các học sinh đã cải thiện chất lượng
              giấc ngủ
            </p>
          </div>
          <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            <div class="bg-white p-6 rounded-lg shadow-md">
              <div class="flex items-center mb-4">
                <div
                  class="w-5 h-5 flex items-center justify-center text-yellow-400"
                >
                  <i class="ri-star-fill"></i>
                </div>
                <div
                  class="w-5 h-5 flex items-center justify-center text-yellow-400"
                >
                  <i class="ri-star-fill"></i>
                </div>
                <div
                  class="w-5 h-5 flex items-center justify-center text-yellow-400"
                >
                  <i class="ri-star-fill"></i>
                </div>
                <div
                  class="w-5 h-5 flex items-center justify-center text-yellow-400"
                >
                  <i class="ri-star-fill"></i>
                </div>
                <div
                  class="w-5 h-5 flex items-center justify-center text-yellow-400"
                >
                  <i class="ri-star-fill"></i>
                </div>
              </div>
              <p class="text-gray-600 mb-6">
                "Trước đây mình thường xuyên thức khuya để học bài, nhưng sau
                khi sử dụng công cụ quản lý thời gian của trang web, mình đã cân
                đối được việc học và nghỉ ngơi. Kết quả học tập tốt hơn mà không
                phải hy sinh giấc ngủ."
              </p>
              <div class="flex items-center">
                <div
                  class="w-10 h-10 rounded-full bg-lightblue flex items-center justify-center text-white font-bold mr-3"
                >
                  N
                </div>
                <div>
                  <h4 class="font-semibold">Nguyễn Minh Ngọc</h4>
                  <p class="text-sm text-gray-500">
                    Học sinh lớp 11, THPT Chu Văn An
                  </p>
                </div>
              </div>
            </div>
            <div class="bg-white p-6 rounded-lg shadow-md">
              <div class="flex items-center mb-4">
                <div
                  class="w-5 h-5 flex items-center justify-center text-yellow-400"
                >
                  <i class="ri-star-fill"></i>
                </div>
                <div
                  class="w-5 h-5 flex items-center justify-center text-yellow-400"
                >
                  <i class="ri-star-fill"></i>
                </div>
                <div
                  class="w-5 h-5 flex items-center justify-center text-yellow-400"
                >
                  <i class="ri-star-fill"></i>
                </div>
                <div
                  class="w-5 h-5 flex items-center justify-center text-yellow-400"
                >
                  <i class="ri-star-fill"></i>
                </div>
                <div
                  class="w-5 h-5 flex items-center justify-center text-yellow-400"
                >
                  <i class="ri-star-half-fill"></i>
                </div>
              </div>
              <p class="text-gray-600 mb-6">
                "Bài đánh giá giấc ngủ đã giúp mình nhận ra rằng mình đang thiếu
                ngủ nghiêm trọng. Sau khi áp dụng các lời khuyên từ trang web,
                mình đã cải thiện được tình trạng mệt mỏi và tập trung tốt hơn
                trong giờ học."
              </p>
              <div class="flex items-center">
                <div
                  class="w-10 h-10 rounded-full bg-lightblue flex items-center justify-center text-white font-bold mr-3"
                >
                  T
                </div>
                <div>
                  <h4 class="font-semibold">Trần Đức Thành</h4>
                  <p class="text-sm text-gray-500">
                    Học sinh lớp 12, THPT Nguyễn Huệ
                  </p>
                </div>
              </div>
            </div>
            <div class="bg-white p-6 rounded-lg shadow-md">
              <div class="flex items-center mb-4">
                <div
                  class="w-5 h-5 flex items-center justify-center text-yellow-400"
                >
                  <i class="ri-star-fill"></i>
                </div>
                <div
                  class="w-5 h-5 flex items-center justify-center text-yellow-400"
                >
                  <i class="ri-star-fill"></i>
                </div>
                <div
                  class="w-5 h-5 flex items-center justify-center text-yellow-400"
                >
                  <i class="ri-star-fill"></i>
                </div>
                <div
                  class="w-5 h-5 flex items-center justify-center text-yellow-400"
                >
                  <i class="ri-star-fill"></i>
                </div>
                <div
                  class="w-5 h-5 flex items-center justify-center text-yellow-400"
                >
                  <i class="ri-star-fill"></i>
                </div>
              </div>
              <p class="text-gray-600 mb-6">
                "AI tư vấn thực sự hiểu được áp lực của học sinh THPT. Nó đã
                giúp mình lập kế hoạch ôn thi đại học mà vẫn đảm bảo đủ thời
                gian ngủ. Kết quả là mình cảm thấy tỉnh táo hơn và ghi nhớ bài
                tốt hơn nhiều."
              </p>
              <div class="flex items-center">
                <div
                  class="w-10 h-10 rounded-full bg-lightblue flex items-center justify-center text-white font-bold mr-3"
                >
                  P
                </div>
                <div>
                  <h4 class="font-semibold">Phạm Thị Mai Anh</h4>
                  <p class="text-sm text-gray-500">
                    Học sinh lớp 12, THPT Lê Quý Đôn
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
      <!-- CTA Section -->
      <section class="py-16 bg-primary text-white">
        <div class="container mx-auto px-4 text-center">
          <h2 class="text-3xl font-bold mb-6">
            Bắt đầu cải thiện giấc ngủ của bạn ngay hôm nay
          </h2>
          <p class="max-w-2xl mx-auto mb-8 text-lg">
            Đánh giá chất lượng giấc ngủ và nhận lời khuyên cá nhân hóa để có
            sức khỏe tốt hơn và kết quả học tập xuất sắc hơn
          </p>
          <div class="flex flex-col sm:flex-row gap-4 justify-center">
            <button
              class="bg-white text-primary font-semibold px-6 py-3 !rounded-button whitespace-nowrap hover:bg-opacity-90 transition duration-300"
            >
              Đánh giá giấc ngủ
            </button>
            <button
              class="bg-transparent border-2 border-white text-white font-semibold px-6 py-3 !rounded-button whitespace-nowrap hover:bg-white hover:bg-opacity-10 transition duration-300"
            >
              Tư vấn AI
            </button>
          </div>
        </div>
      </section>
    </main>
    <!-- Footer -->
    <footer class="bg-gray-900 text-white pt-12 pb-6">
      <div class="container mx-auto px-4">
        <div class="grid grid-cols-1 md:grid-cols-4 gap-8 mb-8">
          <div>
            <div class="flex items-center mb-4">
              <div class="w-10 h-10 flex items-center justify-center mr-2">
                <i class="ri-moon-fill ri-2x text-lightblue"></i>
              </div>
              <h3 class="text-xl font-['Pacifico'] text-lightblue">
                SleepWell
              </h3>
            </div>
            <p class="text-gray-400 mb-4">
              Nâng cao chất lượng giấc ngủ cho học sinh THPT Việt Nam, giúp các
              em có sức khỏe tốt và đạt kết quả học tập xuất sắc.
            </p>
            <div class="flex space-x-4">
              <a
                href="#"
                class="w-8 h-8 flex items-center justify-center bg-gray-800 rounded-full hover:bg-lightblue transition duration-300"
              >
                <i class="ri-facebook-fill"></i>
              </a>
              <a
                href="#"
                class="w-8 h-8 flex items-center justify-center bg-gray-800 rounded-full hover:bg-lightblue transition duration-300"
              >
                <i class="ri-instagram-line"></i>
              </a>
              <a
                href="#"
                class="w-8 h-8 flex items-center justify-center bg-gray-800 rounded-full hover:bg-lightblue transition duration-300"
              >
                <i class="ri-youtube-line"></i>
              </a>
            </div>
          </div>
          <div>
            <h4 class="text-lg font-semibold mb-4">Liên kết nhanh</h4>
            <ul class="space-y-2">
              <li>
                <a
                  href="#"
                  class="text-gray-400 hover:text-white transition duration-300"
                  >Trang chủ</a
                >
              </li>
              <li>
                <a
                  href="#"
                  class="text-gray-400 hover:text-white transition duration-300"
                  >Đánh giá giấc ngủ</a
                >
              </li>
              <li>
                <a
                  href="#"
                  class="text-gray-400 hover:text-white transition duration-300"
                  >Tư vấn AI</a
                >
              </li>
              <li>
                <a
                  href="#"
                  class="text-gray-400 hover:text-white transition duration-300"
                  >Bài viết</a
                >
              </li>
              <li>
                <a
                  href="#"
                  class="text-gray-400 hover:text-white transition duration-300"
                  >Về chúng tôi</a
                >
              </li>
            </ul>
          </div>
          <div>
            <h4 class="text-lg font-semibold mb-4">Tài nguyên</h4>
            <ul class="space-y-2">
              <li>
                <a
                  href="#"
                  class="text-gray-400 hover:text-white transition duration-300"
                  >Thư viện bài viết</a
                >
              </li>
              <li>
                <a
                  href="#"
                  class="text-gray-400 hover:text-white transition duration-300"
                  >Hướng dẫn sử dụng</a
                >
              </li>
              <li>
                <a
                  href="#"
                  class="text-gray-400 hover:text-white transition duration-300"
                  >Câu hỏi thường gặp</a
                >
              </li>
              <li>
                <a
                  href="#"
                  class="text-gray-400 hover:text-white transition duration-300"
                  >Chính sách bảo mật</a
                >
              </li>
              <li>
                <a
                  href="#"
                  class="text-gray-400 hover:text-white transition duration-300"
                  >Điều khoản sử dụng</a
                >
              </li>
            </ul>
          </div>
          <div>
            <h4 class="text-lg font-semibold mb-4">Liên hệ</h4>
            <ul class="space-y-2">
              <li class="flex items-start">
                <div
                  class="w-5 h-5 flex items-center justify-center mt-1 mr-2 text-lightblue"
                >
                  <i class="ri-mail-line"></i>
                </div>
                <span class="text-gray-400">contact@sleepwell.edu.vn</span>
              </li>
              <li class="flex items-start">
                <div
                  class="w-5 h-5 flex items-center justify-center mt-1 mr-2 text-lightblue"
                >
                  <i class="ri-phone-line"></i>
                </div>
                <span class="text-gray-400">028 1234 5678</span>
              </li>
              <li class="flex items-start">
                <div
                  class="w-5 h-5 flex items-center justify-center mt-1 mr-2 text-lightblue"
                >
                  <i class="ri-map-pin-line"></i>
                </div>
                <span class="text-gray-400"
                  >123 Nguyễn Huệ, Quận 1, TP. Hồ Chí Minh</span
                >
              </li>
            </ul>
          </div>
        </div>
        <div
          class="border-t border-gray-800 pt-6 flex flex-col md:flex-row justify-between items-center"
        >
          <p class="text-gray-400 text-sm mb-4 md:mb-0">
            © 2025 SleepWell. Tất cả các quyền được bảo lưu.
          </p>
          <div class="flex space-x-4">
            <a
              href="#"
              class="text-gray-400 text-sm hover:text-white transition duration-300"
              >Chính sách bảo mật</a
            >
            <a
              href="#"
              class="text-gray-400 text-sm hover:text-white transition duration-300"
              >Điều khoản sử dụng</a
            >
            <a
              href="#"
              class="text-gray-400 text-sm hover:text-white transition duration-300"
              >Cookie</a
            >
          </div>
        </div>
      </div>
    </footer>
    <script>
      document.addEventListener("DOMContentLoaded", function () {
        // Counter animation
        function animateCounter(elementId, targetValue, duration) {
          const element = document.getElementById(elementId);
          const startValue = 0;
          const increment = targetValue / (duration / 16);
          let currentValue = startValue;
          const timer = setInterval(() => {
            currentValue += increment;
            if (currentValue >= targetValue) {
              clearInterval(timer);
              currentValue = targetValue;
            }
            element.textContent = Math.floor(currentValue).toLocaleString();
          }, 16);
        }
        animateCounter("visitor-count", 12458, 2000);
        animateCounter("assessment-count", 8721, 2000);
        animateCounter("consultation-count", 5392, 2000);
      });
    </script>
  </body>
</html>
