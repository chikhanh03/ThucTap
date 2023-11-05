<template>
  <div class="text-gray-600 font-Roboto">
    <div class="relative mb-24">
    <div class="">
      <button @click="prevImage"
        class="absolute left-0 top-1/2 transform -translate-y-1/2 bg-gray-300 p-2 rounded-full opacity-50 hover:opacity-100">
        &lt;
      </button>
      <img :src="images[currentImage]" alt="Carousel Image" class="mx-auto slide-image" />
      <button @click="nextImage"
        class="absolute right-0 top-1/2 transform -translate-y-1/2 bg-gray-300 p-2 rounded-full opacity-50 hover:opacity-100">
        &gt;
      </button>
    </div>
  </div>


  <div class="flex sm:flex-row flex-col mb-40 mx-5">
    <div class="flex sm:w-5/12 mt-10 2xl:ml-36 sm:flex-col mr-10 ">
      <div class="fade-in">
        <div class="font-bold text-3xl mb-10">02</div>

        <div class="font-bold text-5xl mb-10 delay-[300ms] duration-[600ms] taos:translate-y-[-200px] taos:opacity-0" data-taos-offset="500">GIỚI THIỆU</div>

        <div class="font-medium 2xl:pr-32 text-xl">Ngôi nhà chính là thành quả chung tay vun đắp và sẻ chia trách nhiệm, là
          đứa
          con tinh thần và cũng là thử thách lớn của đời người. Pixel - Company mong muốn trở thành nhà cung cấp dịch vụ
          xây dựng dân dụng giá trị gia tăng, hướng đến trở thành một mô hình chuẩn mực và tiên phong trong lĩnh vực xây
          dựng tại thị trường Việt Nam.</div>
      </div>
    </div>
    <div class="flex sm:w-7/12 mt-10 2xl:mr-36">
      <div class="flex flex-col">
        <div class="flex font-bold mb-7 mt-20">
          <div class="flex-auto w-6/12">
            <img src="https://theme.hstatic.net/1000122243/1000533602/14/icon1.png?v=45" alt="">
            <p class="mt-6 font-bold text-xl">Thiết kế - Thi công xây dựng</p>
          </div>
          <div class="flex-auto w-6/12">
            <img src="https://theme.hstatic.net/1000122243/1000533602/14/icon2.png?v=45" alt="">
            <p class="mt-6 font-bold text-xl">Quy hoạch đô thị</p>
          </div>
        </div>

        <div class="pr-4 mb-7">
          <p><b>TƯ DUY NGHỀ NGHIỆP:</b> Tạo ra là kết quả của quá trình đầu tư về trí tuệ, thẩm mỹ và tinh thần nhằm
            mang
            lại một
            không gian sống tiện ích và kết nối.</p>
        </div>
        <div class="pr-4">
          <p><b>TẦM NHÌN & SỨ MẠNG:</b> Xác định nhu cầu và thị hiếu nhà theo xu hướng ngày càng nâng cao chất lượng
            cuộc
            sống
            dựa trên giá trị vật chất và tinh thần, đặt ra những yêu cầu khắt khe hơn về dịch vụ xây dựng dân dụng. Cập
            nhật xu thế, nắm bắt nhu cầu trong quy hoạch nhà ở theo hướng lâu dài, đó là những giá trị mà chúng tôi đang
            theo đuổi trong suốt quá trình từ xây dựng ý tưởng đến hoàn thành công trình.</p>
        </div>
      </div>
    </div>
  </div>


  <div class="h-[650px] bg-[url('/img/bg-03.jpg')] bg-cover bg-no-repeat  mb-20">
    <div class="flex w-full h-full  py-36 px-5 text-right text-slate-700">
      <div class="lg:w-1/2"></div>
      <div class="lg:w-1/2 sm:px-20">
        <div class="font-bold text-4xl mb-10">03</div>
        <div class="uppercase text-5xl">Chúng tôi là ai?</div>
        <div>Ngôi nhà chính là thành quả chung tay vun đắp và sẻ chia trách nhiệm, là đứa con tinh thần và cũng là thử
          thách
          lớn của đời người. Pixel - Company mong muốn trở thành nhà cung cấp dịch vụ xây dựng dân dụng giá trị gia tăng,
          hướng đến trở thành một mô hình chuẩn mực và tiên phong trong lĩnh vực xây dựng tại thị trường Việt Nam.</div>
      </div>
    </div>
  </div>


  <div class="mb-48 2xl:mx-40 sm:mx-10 mx-2">
    <div class="font-bold w-full mb-10">
      <div class="text-3xl mb-12 w-40 border-b-2 pb-4">
        04
      </div>
      <div class="text-5xl">
        Dịch vụ
      </div>
    </div>
    <div class="w-full mx-auto">
      <div class="grid lg:grid-cols-2 sm:gap-4 mb-10">
        <div class="border-l-2 border-black h-auto p-8 sm:w-full w-[350px] mb-5">
          <div class="w-full mx-auto">
            <div class="flex mb-5">
              <img class="mr-10 h-[53px]" src="/img/icondv1.webp" alt="">
              <a class="w-[350px] font-bold text-xl" href="">Pixel Company - Thi công xây dựng
                Chuyên nghiệp - Tâm huyết</a>
            </div>
            <div class="">
              Chuẩn mực trong từng công tác xây dựng công trình, sử dụng vật tư đảm bảo chất lượng có thương hiệu trên thị
              trường, sản xuất và thực hiện lắp đặt các vật dụng nội thất: trần thạch cao, xây trát, sơn bả, sản xuất đồ
              gỗ tự nhiên và công nghiệp, làm sắt thép, inox, nhôm kính, cửa cuốn,... Cung cấp dịch vụ trọn gói phù hợp
              theo mong muốn của khách hàng. Luôn theo dõi chặt chẽ để đảm bảo chất lượng đầu ra hoàn hảo, đúng theo kỹ
              thuật và thiết kế đã thống nhất trước đó.
            </div>
          </div>
        </div>
        <div class="border-l-2 border-black h-auto p-8 sm:w-full w-[350px] mb-5">
          <div>
            <div class="flex w-full mx-auto mb-5">
              <img class="mr-10 h-[53px]" src="/img/icondv2.png" alt="">
              <a class="w-[350px] font-bold text-xl" href="">Pixel Company - Thiết kế nội thất
                Hiện đại - Sang trọng</a>
            </div>
            <div>
              Được tư vấn nhiệt tình và hoàn toàn miễn phí. Có ngay một giải pháp từng phần hay tổng thể cho không gian mà
              khách hàng mong muốn. Không gian mà khách hàng mong muốn sẽ được kiến tạo bởi đội ngũ Kiến trúc sư đầy nhiệt
              huyết và giàu kinh nghiệm. Được đảm bảo chất lượng tốt nhất, tiến độ nhanh nhất với chi phí hợp lý nhất. Sở
              hữu ngay một không gian sống, kinh doanh thẩm mỹ, tiện nghi một cách nhanh nhất.
            </div>
          </div>
        </div>
      </div>
      <div class="grid lg:grid-cols-2 gap-4">
        <div class="border-l-2 border-black h-auto p-8 sm:w-full w-[350px] mb-5">
          <div>
            <div class="flex w-full mx-auto mb-5">
              <img class="mr-10 h-[53px]" src="/img/icondv3.webp" alt="">
              <a class="w-[350px] font-bold text-xl" href="">Pixel Company - Thiết kế kiến trúc
                Sáng tạo - Đậm chất phương Tây</a>
            </div>
            <div>
              Với đội ngũ được đào tạo chuyên sâu về Kiến trúc, các Kiến trúc sư Pixel - Company sẽ tư vấn, mô tả chi tiết
              và thực tế căn nhà từ những ý tưởng, nhu cầu ban đầu: như ngôi nhà sẽ xây theo phong cách hiện đại hay cổ
              điển; căn nhà sẽ được bố trí không gian cụ thể bao gồm phòng nào ở tầng nào; hay là căn nhà không chỉ dùng
              cho hai thế hệ, có thể bố trí phòng sao cho trong tương lai ngôi nhà vẫn đảm bảo nhu cầu sử dụng của gia
              chủ.
            </div>
          </div>
        </div>
        <div class="border-l-2 border-black h-auto p-8 sm:w-full w-[350px] mb-5">
          <div>
            <div class="flex w-full mx-auto mb-5">
              <img class="mr-10 h-[53px]" src="/img/icondv4.webp" alt="">
              <a class="w-[350px] font-bold text-xl" href="">Pixel Company - Cung cấp vật liệu xây dựng
                Bền vững - Thân thiện</a>
            </div>
            <div>
              Chúng tôi có hệ thống kho hàng khắp trên tất cả các quận tại Hồ Chí Minh và các tỉnh lân cận, cùng với đó
              đội ngũ chuyên nghiệp bao gồm: Nhân viên tư vấn chuyên nghiệp nhiệt tình, nhà xưởng,kho hàng và xe tải lớn
              nhỏ để vận chuyển tới tận công trình cho khách. Quý khách hàng đến với Pixel - Company có thể yên tâm về giá
              sản phẩm luôn là báo giá mới nhất cập nhật từ các nhà máy sản xuât,với tiêu chí chất lượng, khối lượng đủ,
              và uy tín cùng phát triển.
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <div class="h-[700px] bg-[url('/img/bg-02.webp')] bg-cover bg-no-repeat  mb-20 bg-center">
    <div class="flex flex-col lg:flex-row w-full h-full  lg:py-36 px-5 text-right text-slate-700">
      <div class="lg:w-1/2 lg:border-r-2 border-black lg:py-24 py-20 text-center">
        <div class="text-7xl font-bold mb-10">
          190
        </div>
        <div class="uppercase text-4xl">
          Khách hàng <br> hài lòng
        </div>
      </div>
      <div class="lg:w-1/2 lg:py-24 py-[75px] text-center">
        <div class="text-7xl font-bold mb-10">
          204
        </div>
        <div class="uppercase text-4xl">
          Dự án <br> hoành thành
        </div>
      </div>
    </div>
  </div>


  <div class="flex flex-col 2xl:mx-40 mb-40 lg:mx-10">
    <div class="h-full w-full mx-auto">
      <div class="text-3xl font-bold w-40 border-b-2 pb-5 mb-10">05</div>
      <div class="uppercase text-5xl font-bold mb-10">
        blogs
      </div>
    </div>
    <div class="md:flex h-full w-full mx-auto mb-16">
      <div class="flex-none">
        <img class="h-[370px] md:w-[370px] w-full" src="/img/blogs01.jpg" alt="">
      </div>
      <div class="2xl:pl-32 md:pl-20 mt-5">
        <div class="font-medium mb-10">
          Bé Nguyễn, Ngày 23 Tháng 09/2016
        </div>
        <div class="font-extralight text-4xl mb-16">
          <a href="">Y COMBINATOR MOVES INTO LATE-STAGE INVESTING?</a>
        </div>
        <div class="">
          According to this Business Insider article, famed startup accelerator Y Combinator (which boasts graduates like
          AirBnB, Dropbox, Reddit) has filed documents with the SEC to start a new venture fund.The Y Combinator
          Continuity Fund I, allegedly in...
        </div>
      </div>
    </div>

    <div class="flex md:flex-row flex-col-reverse h-full w-full mx-auto mb-16">
      <div class="2xl:pr-32 md:pr-20 mt-5 text-right">
        <div class="font-medium mb-10">
          Bé Nguyễn, Ngày 23 Tháng 09/2016
        </div>
        <div class="font-extralight text-4xl mb-16">
          <a href="">VIETNAM PLANS TO LAUNCH A NANO SATELLITE INTO ORBIT IN 2016</a>
        </div>
        <div class="">
          Recently, Vietnam announced plans to send a 10 kilogram nano-satellite into orbit in 2016, according to
          Vietnamplus. This project is designed by a team made up of 100 percent Vietnamese engineers and experts. This
          nano-statellite...
        </div>
      </div>
      <div class="flex-none">
        <img class="h-[370px] md:w-[370px] w-full" src="/img/blogs02.jpg" alt="">
      </div>
    </div>

    <div class="md:flex h-full w-full mx-auto mb-16">
      <div class="flex-none">
        <img class="h-[370px] md:w-[370px] w-full" src="/img/blogs03.jpg" alt="">
      </div>
      <div class="2xl:pl-32 md:pl-20 mt-5">
        <div class="font-medium mb-10">
          Bé Nguyễn, Ngày 23 Tháng 09/2016
        </div>
        <div class="font-extralight text-4xl mb-16">
          <a href="">WHAT ARE THE ONLINE PAYMENT SYSTEMS AVAILABLE IN VIETNAM?</a>
        </div>
        <div class="">
          Hi TIA community,I’ve been trying to do some research regarding online payment systems in Vietnam.Most of the
          feedback I gathered is that in Vietnam, online payments systems are still in the early adoption stage.Some
          research from 2013...
        </div>
      </div>
    </div>

    <div class="flex md:flex-row flex-col-reverse h-full w-full mx-auto">
      <div class="2xl:pr-32 md:pr-20 mt-5 text-right">
        <div class="font-medium mb-10">
          Bé Nguyễn, Ngày 23 Tháng 09/2016
        </div>
        <div class="font-extralight text-4xl mb-16">
          <a href="">A COMPLETE LIST OF THE 18 PAYMENT PLAYERS IN VIETNAM</a>
        </div>
        <div class="">
          MobiviFounded by a Vietnamese-American multi-millionaire, Mobivi is one of the biggest names in the Vietnamese
          payment space, though mainly because of how much money it is carrying, rumored to be over $30 million. Mobivi
          has...
        </div>
      </div>
      <div class="flex-none">
        <img class="h-[370px] md:w-[370px] w-full" src="/img/blogs04.jpg" alt="">
      </div>
    </div>
  </div>



  <div class="h-[700px] bg-[url('/img/bg-06.jpg')] bg-cover bg-no-repeat  mb-20">
    <div class="flex w-full h-full  py-36 px-5 text-right text-slate-700">
      <div class="w-7/12"></div>
      <div class="lg:w-5/12 right-0">
        <div class="font-bold text-4xl pb-10">
          06
        </div>
        <div class="uppercase text-5xl font-bold mb-10">Mục tiêu</div>
        <div class="mb-3">
          <p>
            Chúng tôi mong muốn trở thành nhà cung cấp dịch vụ xây dựng dân dụng giá trị gia tăng, hướng đến trở thành một
            mô hình chuẩn mực và tiên phong trong lĩnh vực xây dựng tại thị trường Việt Nam.
          </p>
        </div>
        <div class="mb-2 font-medium">
          > DỊCH VỤ CSKH THÂN THIỆN
        </div>
        <div class="mb-2 font-medium">
          > ÁP DỤNG CÔNG NGHỆ MỚI
        </div>
        <div class="mb-2 font-medium">
          > KHÁCH HÀNG HÀI LÒNG 100%
        </div>
        <div class="mb-2 font-medium">
          > ĐẢM BẢO CHẤT LƯỢNG
        </div>
        <div class="mb-2 font-medium">
          > GIÁ CẢ HỢP LÝ
        </div>
      </div>
    </div>
  </div>

  <div class="flex flex-col 2xl:mx-40 mb-40 sm:mx-10">
    <div class="h-full w-full mx-auto">
      <div class="text-3xl font-bold w-40 border-b-2 pb-5 mb-10">07</div>
      <div class="uppercase text-5xl font-bold mb-10">
        Đội ngũ nhân viên
      </div>
    </div>
    <div class="flex lg:flex-row flex-col lg:mx-auto sm:mx-10 mx-10">
      <div class="flex sm:flex-row flex-col lg:w-1/2 h-full mb-10">
        <div class="flex-none">
          <img class="md:h-[270px] md:w-[270px] h-auto w-auto" src="/img/nhanvien01.jpg" alt="">
        </div>
        <div class="sm:mx-10">
          <div class="uppercase text-4xl mb-6">
            Khôi <br> nguyên
          </div>
          <div class="font-medium mb-6  ">
            Giám đốc điều hành
          </div>
          <div>
            Giám đốc Khôi Nguyên là người chịu trách nhiệm cho toàn hoạt động xảy ra hàng ngày của công ty, là người đứng
            đầu luôn...
          </div>
        </div>
      </div>

      <div class="flex sm:flex-row flex-col lg:w-1/2 h-full mb-10">
        <div class="flex-none">
          <img class="md:h-[270px] md:w-[270px] h-auto w-auto" src="/img/nhanvien02.jpg" alt="">
        </div>
        <div class="sm:mx-10 ">
          <div class="uppercase text-4xl mb-6">
            Thanh <br> thủy
          </div>
          <div class="font-medium mb-6  ">
            Kiến trúc sư
          </div>
          <div>
            KTS. Thanh Thủy, một kiến trúc sư giỏi, đã gia nhập vào Pixel Company từ những ngày mới thành lập, cô có tay
            nghề cao,...
          </div>
        </div>
      </div>
    </div>

    <div class="flex lg:flex-row flex-col lg:mx-auto sm:mx-10 mx-10">
      <div class="flex sm:flex-row flex-col-reverse lg:w-1/2 h-full mb-10">
        <div class="sm:mx-10 sm:text-right">
          <div class="uppercase text-4xl mb-6">
            Hoàng<br> tường
          </div>
          <div class="font-medium mb-6  ">
            Tư vấn pháp lý
          </div>
          <div>
            Tư vấn viên Hoàng Tường chịu trách nhiệm tư vấn pháp lý các dự án công trình cho khách hàng mà chúng tôi phụ
            trách.
          </div>
        </div>
        <div class="flex-none">
          <img class="md:h-[270px] md:w-[270px] h-auto w-auto" src="/img/nhanvien03.jpg" alt="">
        </div>
      </div>

      <div class="flex sm:flex-row flex-col-reverse lg:w-1/2 h-full mb-10">
        <div class="sm:mx-10 sm:text-right">
          <div class="uppercase text-4xl mb-6">
            Minh <br> thông
          </div>
          <div class="font-medium mb-6  ">
            Kỹ sư xây dựng
          </div>
          <div>
            Minh Thông là người quản lý và giám sát quá trình thi công xây dựng. Chịu trách nghiệm điều hướng và quy định
            thời...
          </div>
        </div>
        <div class="flex-none">
          <img class="md:h-[270px] md:w-[270px] h-auto w-auto" src="/img/nhanvien04.jpg" alt="">
        </div>
      </div>
    </div>
  </div>



  <div class="sm:h-[700px] h-[850px] bg-[url('/img/bg-08.jpg')] bg-cover bg-no-repeat bg-center  mb-20">
    <div class="flex flex-col w-full h-full  md:py-32 px-5 text-slate-700">
      <div class="text-center w-full h-auto">
        <div class="text-3xl font-medium mb-10">
          08
        </div>
        <div class="text-5xl uppercase font-bold mb-10">
          nhận xét
        </div>
      </div>
      <div class="flex md:flex-row flex-col justify-between md:gap-10 gap-2 md:mx-10">
        <div class="">
          <div class="mb-10">
            Điều tôi ấn tượng đó là khả năng liên lạc, phối hợp trong suốt dự án. Và với đội ngũ chuyên môn cao đã mang
            đến cho tôi những giải pháp hoàn hảo. Tôi sẽ tiếp tục chọn Pixel Company cho những dự án sau.
          </div>
          <div>
            TOM TEEN
          </div>
        </div>
        <div>
          <div class="mb-10">
            Là khách hàng của Pixel Company, chúng tôi thực sự hài lòng về các bạn. Từ ngày sử dụng dịch vụ tại Pixel
            Company, chúng tôi đã được hỗ trợ rất tốt và được nhiều khách hàng lựa chọn hơn.
          </div>
          <div>
            MELANIE BLOOM
          </div>
        </div>
        <div>
          <div class="mb-10">
            Pixel Company không những hỗ trợ và tư vấn về dịch vụ mà còn đưa ra giải pháp tích cực để giúp nâng cao doanh
            số bán hàng. Tôi thực sự hài lòng về dịch vụ và thái độ chăm sóc khách hàng của Pixel Company.
          </div>
          <div>
            MICHAEL RAT
          </div>
        </div>
      </div>
    </div>
  </div>


  <div class="flex lg:flex-row flex-col-reverse 2xl:mx-36 lg:mx-1 sm:mx-10 mb-20">
    <div class="flex-auto lg:w-5/12">
      <div class="h-23 w-40 text-2xl font-bold border-b-4 border-black mb-10">
        09
      </div>
      <div class="text-6xl font-bold mb-16">
        <p>GIỚI THIỆU</p>
      </div>
      <div class="text-4xl mb-10">
        <p>ĐỊA CHỈ:</p>
      </div>
      <p class="mb-3">Tầng 4, Tòa nhà Flemington, 182 Lê Đại Hành, P.15, Q.11, HCM.</p>
      <p class="mb-3">1900.636.099</p>
      <p class="mb-3">hi@haravan.com</p>
      <p class="mb-24">7 ngày/tuần ftừ 9:00 SA - 7:00 CH</p>
      <div class="flex flex-row mb-24">
        <div class="mr-5"><svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="currentColor" viewBox="0 0 24 24">
            <path
              d="M9 8h-3v4h3v12h5v-12h3.642l.358-4h-4v-1.667c0-.955.192-1.333 1.115-1.333h2.885v-5h-3.808c-3.596 0-5.192 1.583-5.192 4.615v3.385z" />
          </svg></div>
        <div class="mr-5"><svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="currentColor" viewBox="0 0 24 24">
            <path
              d="M24 4.557c-.883.392-1.832.656-2.828.775 1.017-.609 1.798-1.574 2.165-2.724-.951.564-2.005.974-3.127 1.195-.897-.957-2.178-1.555-3.594-1.555-3.179 0-5.515 2.966-4.797 6.045-4.091-.205-7.719-2.165-10.148-5.144-1.29 2.213-.669 5.108 1.523 6.574-.806-.026-1.566-.247-2.229-.616-.054 2.281 1.581 4.415 3.949 4.89-.693.188-1.452.232-2.224.084.626 1.956 2.444 3.379 4.6 3.419-2.07 1.623-4.678 2.348-7.29 2.04 2.179 1.397 4.768 2.212 7.548 2.212 9.142 0 14.307-7.721 13.995-14.646.962-.695 1.797-1.562 2.457-2.549z" />
          </svg></div>
        <div class="mr-5"><svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="currentColor" viewBox="0 0 24 24">
            <path
              d="M7 11v2.4h3.97c-.16 1.029-1.2 3.02-3.97 3.02-2.39 0-4.34-1.979-4.34-4.42 0-2.44 1.95-4.42 4.34-4.42 1.36 0 2.27.58 2.79 1.08l1.9-1.83c-1.22-1.14-2.8-1.83-4.69-1.83-3.87 0-7 3.13-7 7s3.13 7 7 7c4.04 0 6.721-2.84 6.721-6.84 0-.46-.051-.81-.111-1.16h-6.61zm0 0 17 2h-3v3h-2v-3h-3v-2h3v-3h2v3h3v2z"
              fill-rule="evenodd" clip-rule="evenodd" />
          </svg></div>
        <div>
          <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="currentColor" viewBox="0 0 24 24">
            <path
              d="M19.615 3.184c-3.604-.246-11.631-.245-15.23 0-3.897.266-4.356 2.62-4.385 8.816.029 6.185.484 8.549 4.385 8.816 3.6.245 11.626.246 15.23 0 3.897-.266 4.356-2.62 4.385-8.816-.029-6.185-.484-8.549-4.385-8.816zm-10.615 12.816v-8l8 3.993-8 4.007z" />
          </svg>
        </div>
      </div>
      <div>
        Copyright © 2023 Pixel Company. Powered by Haravan.
      </div>
    </div>
    <div class="flex-auto lg:w-6/12 mt-20">
      <iframe
        src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3919.310729061172!2d106.6539626784669!3d10.787496261978522!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x31752ecbb6275cc3%3A0x634b1cfb9f2ed0be!2zNTYgVsOibiBDw7RpLCBwaMaw4budbmcgNywgVMOibiBCw6xuaCwgSOG7kyBDaMOtIE1pbmgsIFZpZXRuYW0!5e0!3m2!1sen!2s!4v1446015505979"
        frameborder="0" width="100%" height="585"></iframe>
    </div>
  </div>
  </div>
</template>


<script>
export default {
  data() {
    return {
      currentImage: 0,
      images: [
        'https://theme.hstatic.net/1000122243/1000533602/14/slide-1.jpg',
        'https://theme.hstatic.net/1000122243/1000533602/14/slide-2.jpg',
        'https://theme.hstatic.net/1000122243/1000533602/14/slide-3.jpg'
      ]
    };
  },
  methods: {
    prevImage() {
      if (this.currentImage === 0) {
        this.currentImage = this.images.length - 1;
      } else {
        this.currentImage--;
      }
    },
    nextImage() {
      if (this.currentImage === this.images.length - 1) {
        this.currentImage = 0;
      } else {
        this.currentImage++;
      }
    }
  }
};


</script>

<style scoped>

.slide-image {
  max-width: 100%;
  max-height: 100%;
  transition: transform 1s ease-in-out;
}

.slide-image.enter-active,
.slide-image-leave-active {
  transition: transform 1s ease-in-out;
}

</style>
