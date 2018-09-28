
# <a name="context"></a><span data-ttu-id="c0cbb-101">context</span><span class="sxs-lookup"><span data-stu-id="c0cbb-101">context</span></span>

### <span data-ttu-id="c0cbb-p101">[Office](Office.md). context</span><span class="sxs-lookup"><span data-stu-id="c0cbb-p101">[Office](Office.md). context</span></span>

<span data-ttu-id="c0cbb-p102">Office.context 命名空间提供所有 Office 应用中的外接程序所使用的共享接口。此列表仅记录 Outlook 外接程序所使用的接口。有关 Office.context 命名空间的完整列表，请参阅[共享 API 中的 Office.context 引用](/javascript/api/office/office.context)。</span><span class="sxs-lookup"><span data-stu-id="c0cbb-p102">The Office.context namespace provides shared interfaces that are used by add-ins in all of the Office apps. This listing documents only those interfaces that are used by Outlook add-ins. For a full listing of the Office.context namespace, see the [Office.context reference in the Shared API](/javascript/api/office/office.context).</span></span>


##### <a name="requirements"></a><span data-ttu-id="c0cbb-106">要求</span><span class="sxs-lookup"><span data-stu-id="c0cbb-106">Requirements</span></span>

|<span data-ttu-id="c0cbb-107">要求</span><span class="sxs-lookup"><span data-stu-id="c0cbb-107">Requirement</span></span>| <span data-ttu-id="c0cbb-108">值</span><span class="sxs-lookup"><span data-stu-id="c0cbb-108">Value</span></span>|
|---|---|
|[<span data-ttu-id="c0cbb-109">最低版本的邮箱要求集</span><span class="sxs-lookup"><span data-stu-id="c0cbb-109">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="c0cbb-110">1.0</span><span class="sxs-lookup"><span data-stu-id="c0cbb-110">1.0</span></span>|
|[<span data-ttu-id="c0cbb-111">适用的 Outlook 模式</span><span class="sxs-lookup"><span data-stu-id="c0cbb-111">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="c0cbb-112">撰写或阅读</span><span class="sxs-lookup"><span data-stu-id="c0cbb-112">Compose or read</span></span>|

### <a name="namespaces"></a><span data-ttu-id="c0cbb-113">命名空间</span><span class="sxs-lookup"><span data-stu-id="c0cbb-113">Namespaces</span></span>

<span data-ttu-id="c0cbb-114">[邮箱](office.context.mailbox.md)-Microsoft Outlook 和 Microsoft Outlook on the web 提供对 Outlook 加载项对象模型的访问。</span><span class="sxs-lookup"><span data-stu-id="c0cbb-114">[mailbox](office.context.mailbox.md) - Provides access to the Outlook add-in object model for Microsoft Outlook and Microsoft Outlook on the web.</span></span>

### <a name="members"></a><span data-ttu-id="c0cbb-115">成员</span><span class="sxs-lookup"><span data-stu-id="c0cbb-115">Members</span></span>

####  <a name="displaylanguage-string"></a><span data-ttu-id="c0cbb-116">displayLanguage :String</span><span class="sxs-lookup"><span data-stu-id="c0cbb-116">displayLanguage :String</span></span>

<span data-ttu-id="c0cbb-117">获取用户针对 Office 主机应用程序的 UI 指定的 RFC 1766 语言标记格式的区域设置（语言）。</span><span class="sxs-lookup"><span data-stu-id="c0cbb-117">Gets the locale (language) in RFC 1766 Language tag format specified by the user for the UI of the Office host application.</span></span>

<span data-ttu-id="c0cbb-118">`displayLanguage` 值反映在 Office 主机应用程序中通过“**文件 > 选项 > 语言**”指定的当前“**显示语言**”设置。</span><span class="sxs-lookup"><span data-stu-id="c0cbb-118">The `displayLanguage` value reflects the current **Display Language** setting specified with **File > Options > Language** in the Office host application.</span></span>

##### <a name="type"></a><span data-ttu-id="c0cbb-119">类型：</span><span class="sxs-lookup"><span data-stu-id="c0cbb-119">Type:</span></span>

*   <span data-ttu-id="c0cbb-120">String</span><span class="sxs-lookup"><span data-stu-id="c0cbb-120">String</span></span>

##### <a name="requirements"></a><span data-ttu-id="c0cbb-121">要求</span><span class="sxs-lookup"><span data-stu-id="c0cbb-121">Requirements</span></span>

|<span data-ttu-id="c0cbb-122">要求</span><span class="sxs-lookup"><span data-stu-id="c0cbb-122">Requirement</span></span>| <span data-ttu-id="c0cbb-123">值</span><span class="sxs-lookup"><span data-stu-id="c0cbb-123">Value</span></span>|
|---|---|
|[<span data-ttu-id="c0cbb-124">最低版本的邮箱要求集</span><span class="sxs-lookup"><span data-stu-id="c0cbb-124">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="c0cbb-125">1.0</span><span class="sxs-lookup"><span data-stu-id="c0cbb-125">1.0</span></span>|
|[<span data-ttu-id="c0cbb-126">适用的 Outlook 模式</span><span class="sxs-lookup"><span data-stu-id="c0cbb-126">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="c0cbb-127">撰写或阅读</span><span class="sxs-lookup"><span data-stu-id="c0cbb-127">Compose or read</span></span>|

##### <a name="example"></a><span data-ttu-id="c0cbb-128">示例</span><span class="sxs-lookup"><span data-stu-id="c0cbb-128">Example</span></span>

```js
function sayHelloWithDisplayLanguage() {
  var myDisplayLanguage = Office.context.displayLanguage;
  switch (myDisplayLanguage) {
    case 'en-US':
      write('Hello!');
      break;
    case 'en-NZ':
      write('G\'day mate!');
      break;
  }
}
// Function that writes to a div with id='message' on the page.
function write(message){
  document.getElementById('message').innerText += message;
}
```

####  <a name="roamingsettings-roamingsettingsjavascriptapioutlook12officeroamingsettings"></a><span data-ttu-id="c0cbb-129">roamingSettings :[RoamingSettings](/javascript/api/outlook_1_2/office.RoamingSettings)</span><span class="sxs-lookup"><span data-stu-id="c0cbb-129">roamingSettings :[RoamingSettings](/javascript/api/outlook_1_2/office.RoamingSettings)</span></span>

<span data-ttu-id="c0cbb-130">获取一个对象，它表示保存到用户邮箱的邮件外接程序的自定义设置或状态。</span><span class="sxs-lookup"><span data-stu-id="c0cbb-130">Gets an object that represents the custom settings or state of a mail add-in saved to a user's mailbox.</span></span>

<span data-ttu-id="c0cbb-131">`RoamingSettings` 对象允许您存储和访问用户邮箱中存储的邮件外接程序的数据，以便从用于访问该邮箱的任何主机客户端应用程序中运行该外接程序时，该外接程序可以使用该数据。</span><span class="sxs-lookup"><span data-stu-id="c0cbb-131">The `RoamingSettings` object lets you store and access data for a mail add-in that is stored in a user's mailbox, so that is available to that add-in when it is running from any host client application used to access that mailbox.</span></span>

##### <a name="type"></a><span data-ttu-id="c0cbb-132">类型:</span><span class="sxs-lookup"><span data-stu-id="c0cbb-132">Type:</span></span>

*   [<span data-ttu-id="c0cbb-133">RoamingSettings</span><span class="sxs-lookup"><span data-stu-id="c0cbb-133">RoamingSettings</span></span>](/javascript/api/outlook_1_2/office.RoamingSettings)

##### <a name="requirements"></a><span data-ttu-id="c0cbb-134">要求</span><span class="sxs-lookup"><span data-stu-id="c0cbb-134">Requirements</span></span>

|<span data-ttu-id="c0cbb-135">要求</span><span class="sxs-lookup"><span data-stu-id="c0cbb-135">Requirement</span></span>| <span data-ttu-id="c0cbb-136">值</span><span class="sxs-lookup"><span data-stu-id="c0cbb-136">Value</span></span>|
|---|---|
|[<span data-ttu-id="c0cbb-137">最低版本的邮箱要求集</span><span class="sxs-lookup"><span data-stu-id="c0cbb-137">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="c0cbb-138">1.0</span><span class="sxs-lookup"><span data-stu-id="c0cbb-138">1.0</span></span>|
|[<span data-ttu-id="c0cbb-139">最低权限级别</span><span class="sxs-lookup"><span data-stu-id="c0cbb-139">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="c0cbb-140">受限</span><span class="sxs-lookup"><span data-stu-id="c0cbb-140">Restricted</span></span>|
|[<span data-ttu-id="c0cbb-141">适用的 Outlook 模式</span><span class="sxs-lookup"><span data-stu-id="c0cbb-141">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="c0cbb-142">撰写或阅读</span><span class="sxs-lookup"><span data-stu-id="c0cbb-142">Compose or read</span></span>|