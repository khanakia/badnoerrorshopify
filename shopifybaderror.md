
## Error
Dated: Sat, 20 Apr 2024 03:53:07 GMT

API URL: https://bad-no.myshopify.com/admin/api/2023-07/graphql.json

### Response Headeres
```json
{
    "Date":
    [
        "Sat, 20 Apr 2024 03:53:07 GMT"
    ],
    "Content-Type":
    [
        "text/html; charset=UTF-8"
    ],
    "Content-Length":
    [
        "12194"
    ],
    "Connection":
    [
        "keep-alive"
    ],
    "X-Sorting-Hat-PodId":
    [
        "198"
    ],
    "X-Sorting-Hat-ShopId":
    [
        "56242602183"
    ],
    "x-dc":
    [
        "gcp-europe-west2,gcp-us-central1,us-central1"
    ],
    "x-request-id":
    [
        "0da5a3be-04fc-4c62-b5b8-8a148711d922-1713585185"
    ],
    "CF-Cache-Status":
    [
        "DYNAMIC"
    ],
    "Report-To":
    [
        "{\"endpoints\":[{\"url\":\"https:\\/\\/a.nel.cloudflare.com\\/report\\/v4?s=bamj%2F3tVHphe%2BWsQ5b6a10fMPf4zpboS%2BNPEW55yP0YpthqvvVZ18K4fOVKBM5WmasuCWy2BVV%2FneeMwprdkuqgeXkoQIpou7sJxY8RH%2BMfdCvOs8Kd1eWHb6m5wv8h0n0E5LRMZ\"}],\"group\":\"cf-nel\",\"max_age\":604800}"
    ],
    "NEL":
    [
        "{\"success_fraction\":0.01,\"report_to\":\"cf-nel\",\"max_age\":604800}"
    ],
    "Server-Timing":
    [
        "cfRequestDuration;dur=1950.999975"
    ],
    "X-XSS-Protection":
    [
        "1; mode=block"
    ],
    "X-Content-Type-Options":
    [
        "nosniff"
    ],
    "X-Permitted-Cross-Domain-Policies":
    [
        "none"
    ],
    "X-Download-Options":
    [
        "noopen"
    ],
    "Server":
    [
        "cloudflare"
    ],
    "CF-RAY":
    [
        "87722f72c94f34c0-DUB"
    ],
    "alt-svc":
    [
        "h3=\":443\"; ma=86400"
    ]
}
```


### Returned Response HTML
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="referrer" content="never">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Something went wrong</title>
    <style>
      * {
        box-sizing: border-box;
        margin: 0;
        padding: 0;
      }
      html {
        font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
        background: #F1F1F1;
        font-size: 62.5%;
        color: #303030;
        min-height: 100%;
      }
      body {
        padding: 0;
        margin: 0;
        line-height: 2.7rem;
      }
      a {
        color: #303030;
        border-bottom: 1px solid #303030;
        text-decoration: none;
        padding-bottom: 1rem;
        transition: border-color 0.2s ease-in;
      }
      a:hover {
        border-bottom-color: #A9A9A9;
      }
      h1 {
        font-size: 1.8rem;
        font-weight: 400;
        margin: 0 0 1.4rem 0;
      }
      p {
        font-size: 1.5rem;
        margin: 0;
      }
      .page {
        padding: 4rem 3.5rem;
        margin: 0;
        display: flex;
        min-height: 100vh;
        flex-direction: column;
      }
      .text-container--main {
        flex: 1;
        display: flex;
        align-items: start;
        margin-bottom: 1.6rem;
      }
      .action {
        background: transparent;
        cursor: pointer;
        border: 1px solid #A9A9A9;
        padding: 1.2rem 2.5rem;
        border-radius: 6px;
        text-decoration: none;
        margin-top: 1.6rem;
        display: inline-block;
        font-size: 1.5rem;
        transition: border-color 0.2s ease-in;
      }
      .action:hover {
        border-color: #000;
      }
      @media all and (min-width:500px) {
        .text-container--main {
          align-items: center;
        }
        .page {
          padding: 7.5rem 10.5rem;
        }
      }
    </style>
  </head>
  <body class="status-error status-code-500">
    <div class="page">
      <div class="text-container text-container--main">
        <div>
          <h1 data-i18n="content-title">There was a problem loading this website</h1>
          <p data-i18n="try-refreshing">Try refreshing the page.</p>
          <p data-i18n="try-again">If the site still doesn't load, please try again in a few minutes.</p>
          <a onclick="window.location.reload();" href="" class="action" data-i18n="refresh-page">Refresh Page</a>
        </div>
      </div>
    </div>
    <script>
      var t = {
        "cs": {
          "title": "Něco se pokazilo",
          "content-title": "Při načítání této webové stránky došlo k chybě",
          "try-refreshing": "Zkuste stránku obnovit.",
          "try-again": "Pokud se stránka ani přesto nenačte, zkuste to znovu za pár minut.",
          "refresh-page": "Obnovit stránku"
        },
        "da": {
          "title": "Der opstod en fejl",
          "content-title": "Der opstod en fejl under indlæsning af dette website",
          "try-refreshing": "Prøv at opdatere siden.",
          "try-again": "Hvis websitet ikke indlæses, kan du prøve igen om nogle få minutter.",
          "refresh-page": "Opdatér siden"
        },
        "de": {
          "title": "Irgendetwas ist schiefgelaufen.",
          "content-title": "Beim Laden dieser Website ist ein Fehler aufgetreten.",
          "try-refreshing": "Versuche, die Seite zu aktualisieren.",
          "try-again": "Wenn die Seite immer noch nicht geladen wird, versuche es bitte in ein paar Minuten erneut.",
          "refresh-page": "Seite neu laden"
        },
        "en": {
          "title": "Something went wrong",
          "content-title": "There was a problem loading this website",
          "try-refreshing": "Try refreshing the page.",
          "try-again": "If the site still doesn't load, please try again in a few minutes.",
          "refresh-page": "Refresh Page"
        },
        "es": {
          "title": "Algo salió mal.",
          "content-title": "Se ha producido un error al descargar el sitio",
          "try-refreshing": "Intenta actualizar la página.",
          "try-again": "Si el sitio no se descarga, por favor, inténtalo en unos minutos.",
          "refresh-page": "Actualizar la página"
        },
        "fi": {
          "title": "Jotain meni pieleen",
          "content-title": "Tämän verkkosivuston lataamisessa oli ongelma",
          "try-refreshing": "Yritä päivittää sivu.",
          "try-again": "Jos sivusto ei vieläkään lataudu, yritä uudelleen muutaman minuutin kuluttua.",
          "refresh-page": "Päivitä sivu"
        },
        "fr": {
          "title": "Une erreur s'est produite",
          "content-title": "Un problème est survenu lors du chargement de ce site",
          "try-refreshing": "Essayez d'actualiser la page.",
          "try-again": "Si le site ne charge toujours pas, veuillez réessayer dans quelques minutes.",
          "refresh-page": "Rafraîchir la page"
        },
        "hi": {
          "title": "कुछ गलत हुआ",
          "content-title": "इस वेबसाइट को लोड करने में समस्या हुई",
          "try-refreshing": "पृष्ठ रीफ़्रेश करके देखें.",
          "try-again": "यदि साइट अभी तक लोड नहीं हुई है, तो कृपया कुछ मिनटों में फिर से कोशिश करें.",
          "refresh-page": "पेज को रीफ़्रेश करें"
        },
        "it": {
          "title": "Si è verificato un errore",
          "content-title": "Si è verificato un problema nel caricamento di questo sito web",
          "try-refreshing": "Prova ad aggiornare la pagina.",
          "try-again": "Se il sito ancora non si carica, per favore riprova tra qualche minuto.",
          "refresh-page": "Aggiorna pagina"
        },
        "ja": {
          "title": "問題が発生しているようです",
          "content-title": "このウェブサイトを読み込む際に問題が発生しました",
          "try-refreshing": "ページを更新してみてください。",
          "try-again": "サイトが読み込まれない場合は、数分後にもう一度お試しください。",
          "refresh-page": "ページを更新する"
        },
        "ko": {
          "title": "문제가 발생했습니다.",
          "content-title": "이 페이지를 로드하는 중 문제가 발생했습니다.",
          "try-refreshing": "페이지를 새로 고침해 보십시오.",
          "try-again": "그래도 사이트가 로드되지 않으면 몇 분 후에 다시 시도하십시오.",
          "refresh-page": "페이지 새로 고침"
        },
        "ms": {
          "title": "Sesuatu tidak kena",
          "content-title": "Terdapat masalah memuatkan laman web ini",
          "try-refreshing": "Cuba segarkan semula halaman.",
          "try-again": "Jika laman web ini masih tidak memuatkan, sila cuba lagi dalam beberapa minit.",
          "refresh-page": "Segarkan semula Halaman"
        },
        "nb": {
          "title": "Noe gikk galt",
          "content-title": "Det oppsto et problem ved lasting av denne nettsiden",
          "try-refreshing": "Prøv å oppdatere siden.",
          "try-again": "Hvis nettstedet fortsatt ikke lastes inn, kan du prøve igjen om noen minutter.",
          "refresh-page": "Oppdater siden"
        },
        "nl": {
          "title": "Er ging iets mis",
          "content-title": "Er is een probleem opgetreden bij het laden van deze website",
          "try-refreshing": "Laad de pagina opnieuw.",
          "try-again": "Als de site nog steeds niet laadt, probeer het over een paar minuten opnieuw.",
          "refresh-page": "Pagina opnieuw laden"
        },
        "pl": {
          "title": "Coś poszło nie tak",
          "content-title": "Podczas ładowania tej strony internetowej wystąpił problem",
          "try-refreshing": "Spróbuj odświeżyć stronę.",
          "try-again": "Jeśli strona nadal się nie ładuje, spróbuj ponownie za kilka minut.",
          "refresh-page": "Odśwież stronę"
        },
        "pt-BR": {
          "title": "Algo deu errado.",
          "content-title": "Houve um problema ao carregar este site",
          "try-refreshing": "Tente atualizar a página.",
          "try-again": "Se o site ainda não carregar, tente novamente dentro de alguns minutos.",
          "refresh-page": "Atualizar a página"
        },
        "pt-PT": {
          "title": "Ocorreu um erro",
          "content-title": "Ocorreu um erro ao carregar este site",
          "try-refreshing": "Experimente atualizar esta página.",
          "try-again": "Se o site continua a não carregar, tente novamente dentro de alguns minutos.",
          "refresh-page": "Atualizar página"
        },
        "sv": {
          "title": "Ett fel uppstod",
          "content-title": "Det gick inte att ladda den här webbplatsen",
          "try-refreshing": "Försök att uppdatera sidan.",
          "try-again": "Försök igen om några minuter om webbplatsen fortfarande inte har laddats.",
          "refresh-page": "Uppdatera sida"
        },
        "th": {
          "title": "เกิดข้อผิดพลาดขึ้น",
          "content-title": "เกิดปัญหาในการโหลดเว็บไซต์นี้",
          "try-refreshing": "โปรดรีเฟรชหน้านี้อีกครั้ง",
          "try-again": "หากเว็บไซต์ยังไม่โหลด โปรดลองอีกครั้งในอีกสักครู่",
          "refresh-page": "รีเฟรชหน้า"
        },
        "tr": {
          "title": "Bir sorun oluştu",
          "content-title": "Bu web sitesi yüklenirken sorun oluştu",
          "try-refreshing": "Sayfayı yenilemeyi deneyin.",
          "try-again": "Sayfa hâlâ yüklenmiyorsa lütfen birkaç dakika sonra tekrar deneyin.",
          "refresh-page": "Sayfayı Yenile"
        },
        "vi": {
          "title": "Đã xảy ra lỗi",
          "content-title": "Đã xảy ra sự cố khi tải trang web này",
          "try-refreshing": "Thử làm mới trang.",
          "try-again": "Nếu trang web vẫn không tải được, vui lòng thử lại sau ít phút.",
          "refresh-page": "Tải lại trang"
        },
        "zh-CN": {
          "title": "出现错误",
          "content-title": "加载此网站时出现问题",
          "try-refreshing": "请尝试刷新页面。",
          "try-again": "如果网站仍未加载，请在几分钟后重试。",
          "refresh-page": "刷新页面"
        },
        "zh-TW": {
          "title": "出了點問題",
          "content-title": "系統載入此網站時發生問題",
          "try-refreshing": "請嘗試重新整理此頁面。",
          "try-again": "如果網站仍未載入，請幾分鐘後再試一次。",
          "refresh-page": "重新整理頁面"
        }
      };
      var language = navigator.languages && navigator.languages[0] || // Chrome and Firefox
        navigator.language || // Most browsers
        navigator.userLanguage || // IE <= 10
        "en";
      language = language.split("-")[0]; // Strip country code
      translations = t[language] || t["en"];
      // Replace language attribute in html
      if (t[language]) {
        document.getElementsByTagName("html")[0].setAttribute("lang", language);
      };
      // Replace title text
      document.title = translations["title"];
      // Replace text in body elements
      for (var id in translations) {
        target = document.querySelector("[data-i18n=" + id + "]");
        if (target != undefined) {
          target.innerHTML = translations[id];
        }
      }
    </script>
  </body>
</html>
  
````



## CURL request
```sh
curl --location 'https://bad-no.myshopify.com/admin/api/2023-07/graphql.json' \
--header 'X-Shopify-Access-Token: XXXXXX' \
--header 'Content-Type: application/json' \
--data '{"query":"mutation metafieldsSet($metafields: [MetafieldsSetInput!]!) {\n    metafieldsSet(metafields: $metafields) {\n        userErrors {\n            field\n            message\n        }\n    }\n}","variables":{"metafields":[{"namespace":"custom","key":"cost","type":"number_integer","value":"2000","ownerId":"gid://shopify/ProductVariant/43540000243911"},{"namespace":"custom","key":"lowest_price_available","type":"single_line_text_field","value":"none","ownerId":"gid://shopify/ProductVariant/43540000243911"},{"namespace":"custom","key":"recommended_retail_price_test","type":"number_decimal","value":"4385.00","ownerId":"gid://shopify/ProductVariant/43540000243911"},{"namespace":"custom","key":"lowest_price_in_period","type":"number_integer","value":"4385","ownerId":"gid://shopify/ProductVariant/43540000243911"},{"namespace":"custom","key":"pricematch_last_checked","type":"date_time","value":"2024-04-20T03:53:05+00:00","ownerId":"gid://shopify/ProductVariant/43540000243911"}]}}'

```



## Graphql Reqeust

```
mutation metafieldsSet($metafields: [MetafieldsSetInput!]!) {
    metafieldsSet(metafields: $metafields) {
        userErrors {
            field
            message
        }
    }
}


-- variables
{
    "metafields": [
  {
    "namespace": "custom",
    "key": "cost",
    "type": "number_integer",
    "value": "2000",
    "ownerId": "gid://shopify/ProductVariant/43540000243911"
  },
  {
    "namespace": "custom",
    "key": "lowest_price_available",
    "type": "single_line_text_field",
    "value": "none",
    "ownerId": "gid://shopify/ProductVariant/43540000243911"
  },
  {
    "namespace": "custom",
    "key": "recommended_retail_price_test",
    "type": "number_decimal",
    "value": "4385.00",
    "ownerId": "gid://shopify/ProductVariant/43540000243911"
  },
  {
    "namespace": "custom",
    "key": "lowest_price_in_period",
    "type": "number_integer",
    "value": "4385",
    "ownerId": "gid://shopify/ProductVariant/43540000243911"
  },
  {
    "namespace": "custom",
    "key": "pricematch_last_checked",
    "type": "date_time",
    "value": "2024-04-20T03:53:05+00:00",
    "ownerId": "gid://shopify/ProductVariant/43540000243911"
  }
]
}
```
