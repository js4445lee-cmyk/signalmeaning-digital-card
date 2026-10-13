# SignalMeaning — free digital cards for real-world introductions

Create and share a digital business card without signing up or installing an app. SignalMeaning gives you a public card link, QR options, contact saving, website embeds, and a compact profile badge.

**[Visit SignalMeaning](https://signalmeaning.com/)** · **[Create a free digital card](https://signalmeaning.com/links/)**

## What you can do

- Start with a name, then optionally add a bio, contact details, up to seven social profiles, and up to ten links.
- Choose a theme and optional profile photo; preview the card before sharing.
- Share a public link, export a card image, or use an online QR code when meeting in person.
- Offer contact saving and an offline contact QR for details that fit in a vCard.
- Put a full, compact, or button card embed—or a profile badge—on a website.

### Common uses

| Setting | Suggested format |
| --- | --- |
| Networking event or conference | Public link or online QR |
| Portfolio or personal site | Compact embed or profile badge |
| Email signature or social profile | Public card link |
| Printed handout | Online QR, or offline contact QR for contact details |

## Working public embed

This is a live, non-personal SignalMeaning demo card. [Open the compact embed](https://signalmeaning.com/embed/links/?variant=compact#eyJ2IjoxLCJuYW1lIjoiU2lnbmFsTWVhbmluZyIsImJpbyI6IkZyZWUgZGlnaXRhbCBjYXJkcyBmb3IgbWVhbmluZ2Z1bCBpbnRyb2R1Y3Rpb25zLiIsInRoZW1lIjoic2ltcGxlIiwibGlua3MiOlt7InRpdGxlIjoiTWFrZSB5b3VyIG93biBmcmVlIGRpZ2l0YWwgY2FyZCIsInVybCI6Imh0dHBzOi8vc2lnbmFsbWVhbmluZy5jb20vbGlua3MvIn1dfQ).

Paste this iframe into your site's HTML:

You can also inspect the standalone [compact embed example](examples/compact-embed.html).

```html
<iframe
  title="SignalMeaning digital card demo"
  src="https://signalmeaning.com/embed/links/?variant=compact#eyJ2IjoxLCJuYW1lIjoiU2lnbmFsTWVhbmluZyIsImJpbyI6IkZyZWUgZGlnaXRhbCBjYXJkcyBmb3IgbWVhbmluZ2Z1bCBpbnRyb2R1Y3Rpb25zLiIsInRoZW1lIjoic2ltcGxlIiwibGlua3MiOlt7InRpdGxlIjoiTWFrZSB5b3VyIG93biBmcmVlIGRpZ2l0YWwgY2FyZCIsInVybCI6Imh0dHBzOi8vc2lnbmFsbWVhbmluZy5jb20vbGlua3MvIn1dfQ"
  width="100%"
  height="180"
  loading="lazy"
  referrerpolicy="no-referrer"
  style="border:0;max-width:100%;border-radius:12px"
></iframe>
```

To embed **your** card, create it in the [Digital Card maker](https://signalmeaning.com/links/), open its Share Kit, choose **Embed widget** or **Profile badge**, and copy the generated HTML. The Share Kit also offers full, compact, and button variants. Keep the complete URL, including the `#` fragment, because it contains the card details. If your site has a Content Security Policy, allow `https://signalmeaning.com` as an iframe source.

## QR and badge tips

- Use the **online card QR** to open the complete public card; the visitor needs an internet connection.
- Use the **offline contact QR** to save contact details without internet. It does not carry the profile photo or all links.
- Choose **Profile badge** in the Share Kit for a small footer or sidebar introduction. Copy the generated code so the sizing matches your card.

## Important limits

- The basic card is free and needs no account. Card details are encoded in its share link, so keep that link. Existing shared links keep the details they had when created.
- An optional uploaded photo is removed after seven days; the card shows initials afterward. Replacing or removing a photo can also affect earlier shares that use it.
- The public card and iframe require JavaScript. Online links and QR codes require internet access.
- Only publish contact details you intend to share publicly. Keep the private edit link private.

The [Digital Card maker](https://signalmeaning.com/links/) shows the current limits and share options. For support, use [SignalMeaning Contact](https://signalmeaning.com/contact/).

## 한국어 안내

SignalMeaning에서는 회원가입이나 앱 설치 없이 무료 디지털 명함을 만들 수 있습니다. [명함 제작기](https://signalmeaning.com/links/)에서 이름과 공개할 정보만 입력한 뒤 링크·QR·웹사이트 Embed·프로필 배지를 선택하세요. 공유 링크는 공개할 정보를 담고 있으므로, 공개 범위를 확인한 후 배포하세요.
