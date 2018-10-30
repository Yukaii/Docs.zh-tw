# <a name="contribute-to-the-aspnet-documentation"></a><span data-ttu-id="1d343-101">參與 ASP.NET 文件</span><span class="sxs-lookup"><span data-stu-id="1d343-101">Contribute to the ASP.NET documentation</span></span>

<span data-ttu-id="1d343-102">本文件涵蓋參與 [ASP.NET 文件網站](https://docs.microsoft.com/aspnet/)所裝載文章和程式碼範例的程序。</span><span class="sxs-lookup"><span data-stu-id="1d343-102">This document covers the process for contributing to the articles and code samples that are hosted on the [ASP.NET documentation site](https://docs.microsoft.com/aspnet/).</span></span> <span data-ttu-id="1d343-103">歡迎您加入修正錯字和新增文章的行列。</span><span class="sxs-lookup"><span data-stu-id="1d343-103">Typo corrections and new articles are welcome contributions.</span></span>

## <a name="how-to-make-a-simple-correction-or-suggestion"></a><span data-ttu-id="1d343-104">如何提出簡單的修正或建議</span><span class="sxs-lookup"><span data-stu-id="1d343-104">How to make a simple correction or suggestion</span></span>

<span data-ttu-id="1d343-105">文章會以 Markdown 檔案形式儲存在存放庫中。</span><span class="sxs-lookup"><span data-stu-id="1d343-105">Articles are stored in the repository as Markdown files.</span></span> <span data-ttu-id="1d343-106">您可以在瀏覽器中，選取瀏覽器視窗右上角的 [編輯] 連結，對 Markdown 檔案內容進行簡易變更。</span><span class="sxs-lookup"><span data-stu-id="1d343-106">Simple changes to the content of a Markdown file are made in the browser by selecting the **Edit** link in the upper-right corner of the browser window.</span></span> <span data-ttu-id="1d343-107">(如果瀏覽器視窗很窄，展開 [選項] 列即可看到 [編輯] 連結)。請依照指示來建立提取要求 (PR)。</span><span class="sxs-lookup"><span data-stu-id="1d343-107">(In a narrow browser window, expand the **options** bar to see the **Edit** link.) Follow the directions to create a pull request (PR).</span></span> <span data-ttu-id="1d343-108">我們將檢閱 PR 並接受它，或建議變更。</span><span class="sxs-lookup"><span data-stu-id="1d343-108">We will review the PR and accept it or suggest changes.</span></span>

## <a name="how-to-make-a-more-complex-submission"></a><span data-ttu-id="1d343-109">如何進行更複雜的提交</span><span class="sxs-lookup"><span data-stu-id="1d343-109">How to make a more complex submission</span></span>

<span data-ttu-id="1d343-110">您需要對 [Git 和 GitHub.com](https://guides.github.com/activities/hello-world/) 有基本了解。</span><span class="sxs-lookup"><span data-stu-id="1d343-110">You need a basic understanding of [Git and GitHub.com](https://guides.github.com/activities/hello-world/).</span></span>

* <span data-ttu-id="1d343-111">建立一則[議題](https://github.com/aspnet/Docs/issues/new)描述您欲執行的動作，例如變更現有的文章或建立新的文章。</span><span class="sxs-lookup"><span data-stu-id="1d343-111">Open an [issue](https://github.com/aspnet/Docs/issues/new) describing what you want to do, such as changing an existing article or creating a new one.</span></span> <span data-ttu-id="1d343-112">我們通常會要求新建議主題的大綱。</span><span class="sxs-lookup"><span data-stu-id="1d343-112">We often request an outline for a new topic suggestion.</span></span> <span data-ttu-id="1d343-113">在您投入更多時間之前，請等候小組的核准。</span><span class="sxs-lookup"><span data-stu-id="1d343-113">Wait for approval from the team before you invest much time.</span></span>
* <span data-ttu-id="1d343-114">派生 [aspnet/Docs](https://github.com/aspnet/Docs/) 存放庫，並針對您的變更建立分支。</span><span class="sxs-lookup"><span data-stu-id="1d343-114">Fork the [aspnet/Docs](https://github.com/aspnet/Docs/) repo and create a branch for your changes.</span></span>
* <span data-ttu-id="1d343-115">將內含變更的 PR 提交給管理員。</span><span class="sxs-lookup"><span data-stu-id="1d343-115">Submit a PR to master with your changes.</span></span>
* <span data-ttu-id="1d343-116">如果您的 PR 被分派到 'cla-required' 標籤，請[完成貢獻授權合約 (CLA)](https://cla.dotnetfoundation.org/)。</span><span class="sxs-lookup"><span data-stu-id="1d343-116">If your PR has the label 'cla-required' assigned, [complete the Contribution License Agreement (CLA)](https://cla.dotnetfoundation.org/).</span></span>
* <span data-ttu-id="1d343-117">回應 PR 意見。</span><span class="sxs-lookup"><span data-stu-id="1d343-117">Respond to PR feedback.</span></span>

<span data-ttu-id="1d343-118">如需此程序進展至發行新文章的範例，請參閱 .NET Docs 存放庫中的[議題&num;67](https://github.com/dotnet/docs/issues/67) 和[提取要求&num;798](https://github.com/dotnet/docs/pull/798)。</span><span class="sxs-lookup"><span data-stu-id="1d343-118">For an example where this process led to publication of a new article, see [Issue &num;67](https://github.com/dotnet/docs/issues/67) and [Pull Request &num;798](https://github.com/dotnet/docs/pull/798) in the .NET Docs repository.</span></span> <span data-ttu-id="1d343-119">新文章為[記錄您的程式碼](https://docs.microsoft.com/dotnet/articles/csharp/codedoc)。</span><span class="sxs-lookup"><span data-stu-id="1d343-119">The new article is [Documenting your code](https://docs.microsoft.com/dotnet/articles/csharp/codedoc).</span></span>

## <a name="docs-authoring-pack-extension-in-visual-studio-code"></a><span data-ttu-id="1d343-120">Visual Studio Code 中的 Docs Authoring Pack 延伸模組</span><span class="sxs-lookup"><span data-stu-id="1d343-120">Docs Authoring Pack extension in Visual Studio Code</span></span> 

<span data-ttu-id="1d343-121">如果您使用 Visual Studio Code 來參與 ASP.NET 文件，您即可藉由安裝 [Docs Authoring Pack](https://marketplace.visualstudio.com/items?itemName=docsmsft.docs-authoring-pack) 延伸模組來提高生產力。</span><span class="sxs-lookup"><span data-stu-id="1d343-121">If you use Visual Studio Code to contribute to the ASP.NET documentation, you can boost your productivity by installing the [Docs Authoring Pack](https://marketplace.visualstudio.com/items?itemName=docsmsft.docs-authoring-pack) extension.</span></span> <span data-ttu-id="1d343-122">該延伸模組會提供各種不同的工具，協助 Markdown linting、程式碼拼字檢查和文章範本。</span><span class="sxs-lookup"><span data-stu-id="1d343-122">The extension provides a variety of tools that helps with Markdown linting, code spell checking, and article templates.</span></span>

## <a name="markdown-syntax"></a><span data-ttu-id="1d343-123">Markdown 語法</span><span class="sxs-lookup"><span data-stu-id="1d343-123">Markdown syntax</span></span>

<span data-ttu-id="1d343-124">文章是以 [DocFX Flavored Markdown](https://dotnet.github.io/docfx/spec/docfx_flavored_markdown.html) 撰寫，也就是 [GitHub Flavored Markdown (GFM)](https://guides.github.com/features/mastering-markdown/) 的超集。</span><span class="sxs-lookup"><span data-stu-id="1d343-124">Articles are written in [DocFx-flavored Markdown](https://dotnet.github.io/docfx/spec/docfx_flavored_markdown.html), which is a superset of [GitHub-flavored Markdown (GFM)](https://guides.github.com/features/mastering-markdown/).</span></span> <span data-ttu-id="1d343-125">如需 ASP.NET 文件中常用 UI 功能的 DFM 語法範例，請參閱 .NET Docs 存放庫樣式指南中的 [Metadata and Markdown Template](https://github.com/dotnet/docs/blob/master/styleguide/template.md) (中繼資料和 Markdown 範本)。</span><span class="sxs-lookup"><span data-stu-id="1d343-125">For examples of DFM syntax for UI features commonly used in the ASP.NET documentation, see [Metadata and Markdown Template](https://github.com/dotnet/docs/blob/master/styleguide/template.md) in the .NET Docs repo style guide.</span></span> 

## <a name="folder-structure-conventions"></a><span data-ttu-id="1d343-126">資料夾結構慣例</span><span class="sxs-lookup"><span data-stu-id="1d343-126">Folder structure conventions</span></span>

<span data-ttu-id="1d343-127">在每個 Markdown 檔案中，可能存在一個影像資料夾和一個範例程式碼資料夾。</span><span class="sxs-lookup"><span data-stu-id="1d343-127">For each Markdown file, a folder for images and a folder for sample code may exist.</span></span> <span data-ttu-id="1d343-128">如果文章是 [fundamentals/configuration/index.md](https://github.com/aspnet/Docs/blob/master/aspnetcore/fundamentals/configuration/index.md)，影像會位於 [fundamentals/configuration/index/\_static](https://github.com/aspnet/Docs/tree/master/aspnetcore/fundamentals/configuration/index/_static) 中，而範例應用程式專案檔會位於 [fundamentals/configuration/index/sample](https://github.com/aspnet/Docs/tree/master/aspnetcore/fundamentals/configuration/index/sample) 中。</span><span class="sxs-lookup"><span data-stu-id="1d343-128">If the article is [fundamentals/configuration/index.md](https://github.com/aspnet/Docs/blob/master/aspnetcore/fundamentals/configuration/index.md), the images are in [fundamentals/configuration/index/\_static](https://github.com/aspnet/Docs/tree/master/aspnetcore/fundamentals/configuration/index/_static) and the sample app project files are in [fundamentals/configuration/index/sample](https://github.com/aspnet/Docs/tree/master/aspnetcore/fundamentals/configuration/index/sample).</span></span> <span data-ttu-id="1d343-129">*fundamentals/configuration/index.md* 檔案中的影像會由下列 Markdown 轉譯：</span><span class="sxs-lookup"><span data-stu-id="1d343-129">An image in the *fundamentals/configuration/index.md* file is rendered by the following Markdown:</span></span>

```
![description of image for alt attribute](configuration/index/_static/imagename.png)
```

<span data-ttu-id="1d343-130">所有影像都應有[替代 (alt) 文字](https://wikipedia.org/wiki/Alt_attribute)。</span><span class="sxs-lookup"><span data-stu-id="1d343-130">All images should have [alternative (alt) text](https://wikipedia.org/wiki/Alt_attribute).</span></span> <span data-ttu-id="1d343-131">如需指定 alt 文字的建議，請參閱線上資源，例如 [WebAIM: Alternative Text](https://webaim.org/techniques/alttext/) (WebAIM：替代文字)。</span><span class="sxs-lookup"><span data-stu-id="1d343-131">For advice on specifying alt text, see online resources, such as [WebAIM: Alternative Text](https://webaim.org/techniques/alttext/).</span></span>

<span data-ttu-id="1d343-132">針對 Markdown 檔案名稱和影像檔案名稱，請使用小寫。</span><span class="sxs-lookup"><span data-stu-id="1d343-132">Use lowercase for Markdown file names and image file names.</span></span>

## <a name="internal-links"></a><span data-ttu-id="1d343-133">內部連結</span><span class="sxs-lookup"><span data-stu-id="1d343-133">Internal links</span></span>

<span data-ttu-id="1d343-134">內部連結應使用目標文章的 `uid` 並搭配 xref 連結 (設為連結內容標題的連結文字)：</span><span class="sxs-lookup"><span data-stu-id="1d343-134">Internal links should use the `uid` of the target article with an xref link (link text is set to the linked content's title):</span></span>

```
<xref:uid_of_the_topic>
```

<span data-ttu-id="1d343-135">如果文章的標題不適用於連結文字 (例如連結文字是句子中的單字或片語)，請使用下列命令來指定 xref 連結和連結文字：</span><span class="sxs-lookup"><span data-stu-id="1d343-135">If the title of the article is unsuitable for link text (for example, a word or phrase in a sentence is the link text), specify the xref link and link text with the following:</span></span>

```
[link text](xref:uid_of_the_topic)
```

<span data-ttu-id="1d343-136">如需詳細資訊，請參閱 [DocFX Cross Reference](https://dotnet.github.io/docfx/spec/docfx_flavored_markdown.html#cross-reference) (DocFX 交互參照)。</span><span class="sxs-lookup"><span data-stu-id="1d343-136">For more information, see the [DocFX Cross Reference](https://dotnet.github.io/docfx/spec/docfx_flavored_markdown.html#cross-reference).</span></span>

## <a name="images-and-screenshots"></a><span data-ttu-id="1d343-137">影像和螢幕擷取畫面</span><span class="sxs-lookup"><span data-stu-id="1d343-137">Images and screenshots</span></span>

<span data-ttu-id="1d343-138">還有一個選擇性步驟，那就是確認文件中使用的所有影像和螢幕擷取畫面均已壓縮，這有助於檔案大小和頁面載入效能。</span><span class="sxs-lookup"><span data-stu-id="1d343-138">As an optional step, ensure that any images and screenshots used in the documentation are compressed, which helps with file size and page load performance.</span></span> <span data-ttu-id="1d343-139">一些熱門的工具包括 TinyPNG (使用 [TinyPNG 網站](https://tinypng.com/)或 [TinyPNG API](https://tinypng.com/developers)) 或 [Image Optimizer](https://marketplace.visualstudio.com/items?itemName=MadsKristensen.ImageOptimizer) Visual Studio 延伸模組。</span><span class="sxs-lookup"><span data-stu-id="1d343-139">A few popular tools include TinyPNG (using the [TinyPNG website](https://tinypng.com/) or the [TinyPNG API](https://tinypng.com/developers)) or the [Image Optimizer](https://marketplace.visualstudio.com/items?itemName=MadsKristensen.ImageOptimizer) Visual Studio extension.</span></span> 

## <a name="code-snippets"></a><span data-ttu-id="1d343-140">程式碼片段</span><span class="sxs-lookup"><span data-stu-id="1d343-140">Code snippets</span></span>

<span data-ttu-id="1d343-141">文章通常會包含程式碼片段，作重點說明之用。</span><span class="sxs-lookup"><span data-stu-id="1d343-141">Articles frequently contain code snippets to illustrate points.</span></span> <span data-ttu-id="1d343-142">DFM 可讓您將程式碼複製到 Markdown 檔案中，或參考不同的程式碼檔案。</span><span class="sxs-lookup"><span data-stu-id="1d343-142">DFM allows you to copy code into the Markdown file or refer to a separate code file.</span></span> <span data-ttu-id="1d343-143">建議盡可能使用不同的程式碼檔案，將程式碼中的錯誤機率降到最低。</span><span class="sxs-lookup"><span data-stu-id="1d343-143">We prefer to use separate code files whenever possible to minimize the chance of errors in the code.</span></span> <span data-ttu-id="1d343-144">程式碼檔案會儲存在存放庫 (使用於先前範例專案所述的資料夾結構) 中。</span><span class="sxs-lookup"><span data-stu-id="1d343-144">The code files are stored in the repo using the folder structure described earlier for sample projects.</span></span> 

<span data-ttu-id="1d343-145">下列範例說明 *configuration/index.md* 檔案中所使用的 [DFM 程式碼片段語法](https://dotnet.github.io/docfx/spec/docfx_flavored_markdown.html#code-snippet)。</span><span class="sxs-lookup"><span data-stu-id="1d343-145">The following examples illustrate [DFM code snippet syntax](https://dotnet.github.io/docfx/spec/docfx_flavored_markdown.html#code-snippet) for use in a *configuration/index.md* file.</span></span>

<span data-ttu-id="1d343-146">若要將完整程式碼檔案轉譯為程式碼片段：</span><span class="sxs-lookup"><span data-stu-id="1d343-146">To render an entire code file as a snippet:</span></span>

```
[!code-csharp[](configuration/index/sample/Program.cs)]
```

<span data-ttu-id="1d343-147">若要使用行號，將一部分檔案轉譯為程式碼片段：</span><span class="sxs-lookup"><span data-stu-id="1d343-147">To render a portion of a file as a snippet by using line numbers:</span></span>

```
[!code-csharp[](configuration/index/sample/Program.cs?range=1-10,20,30,40-50]
[!code-html[](configuration/index/sample/Views/Home/Index.cshtml?range=1-10,20,30,40-50]
```

<span data-ttu-id="1d343-148">針對 C# 程式碼片段，請參考 [C# 區域](https://docs.microsoft.com/dotnet/csharp/language-reference/preprocessor-directives/preprocessor-region)。</span><span class="sxs-lookup"><span data-stu-id="1d343-148">For C# snippets, reference a [C# region](https://docs.microsoft.com/dotnet/csharp/language-reference/preprocessor-directives/preprocessor-region).</span></span> <span data-ttu-id="1d343-149">請盡可能使用區域而不是行號，因為程式碼檔案中的行號通常會變更，而變得與 Markdown 中的行號參考不同步。</span><span class="sxs-lookup"><span data-stu-id="1d343-149">Whenever possible, use regions rather than line numbers because line numbers in a code file tend to change and become out of sync with line number references in Markdown.</span></span> <span data-ttu-id="1d343-150">C# 區域可以是巢狀的。</span><span class="sxs-lookup"><span data-stu-id="1d343-150">C# regions can be nested.</span></span> <span data-ttu-id="1d343-151">如果參考外部區域，則不會轉譯程式碼片段中的內部 `#region` 和 `#endregion` 指示詞。</span><span class="sxs-lookup"><span data-stu-id="1d343-151">If referencing the outer region, the inner `#region` and `#endregion` directives aren't rendered in a snippet.</span></span> 

<span data-ttu-id="1d343-152">若要轉譯名為 "snippet_Example" 的 C# 區域：</span><span class="sxs-lookup"><span data-stu-id="1d343-152">To render a C# region named "snippet_Example":</span></span>

```
[!code-csharp[](configuration/index/sample/Program.cs?name=snippet_Example)]
```

<span data-ttu-id="1d343-153">若要醒目提示轉譯程式碼片段中所選取的行 (通常會以黃色背景色彩呈現)：</span><span class="sxs-lookup"><span data-stu-id="1d343-153">To highlight selected lines in a rendered snippet (usually renders as yellow background color):</span></span>

```
[!code-csharp[](configuration/index/sample/Program.cs?name=snippet_Example&highlight=1-3,10,20-25)]
[!code-csharp[](configuration/index/sample/Program.cs?range=10-20&highlight=1-3]
[!code-html[](configuration/index/sample/Views/Home/Index.cshtml?range=10-20&highlight=1-3]
[!code-javascript[](configuration/index/sample/UsingOptionsSample.csproj?range=10-20&highlight=1-3]
```

## <a name="test-changes-with-docfx"></a><span data-ttu-id="1d343-154">使用 DocFX 測試變更</span><span class="sxs-lookup"><span data-stu-id="1d343-154">Test changes with DocFX</span></span>

<span data-ttu-id="1d343-155">使用 [DocFX 命令列工具](https://dotnet.github.io/docfx/tutorial/docfx_getting_started.html#2-use-docfx-as-a-command-line-tool)測試您的變更，這會建立本機裝載的網站版本。</span><span class="sxs-lookup"><span data-stu-id="1d343-155">Test your changes with the [DocFX command-line tool](https://dotnet.github.io/docfx/tutorial/docfx_getting_started.html#2-use-docfx-as-a-command-line-tool), which creates a locally hosted version of the site.</span></span> <span data-ttu-id="1d343-156">DocFX 不會轉譯 docs.microsoft.com 建立的樣式和網站延伸模組。</span><span class="sxs-lookup"><span data-stu-id="1d343-156">DocFX doesn't render style and site extensions created for docs.microsoft.com.</span></span>

<span data-ttu-id="1d343-157">DocFX 需要：</span><span class="sxs-lookup"><span data-stu-id="1d343-157">DocFX requires:</span></span>

* <span data-ttu-id="1d343-158">Windows 上的 .NET Framework。</span><span class="sxs-lookup"><span data-stu-id="1d343-158">.NET Framework on Windows.</span></span>
* <span data-ttu-id="1d343-159">適用於 Linux 或 macOS 的 Mono。</span><span class="sxs-lookup"><span data-stu-id="1d343-159">Mono for Linux or macOS.</span></span> 

### <a name="windows-instructions"></a><span data-ttu-id="1d343-160">Windows 指示</span><span class="sxs-lookup"><span data-stu-id="1d343-160">Windows instructions</span></span>

* <span data-ttu-id="1d343-161">從 [DocFX 版本](https://github.com/dotnet/docfx/releases)下載並解壓縮 *docfx.zip*。</span><span class="sxs-lookup"><span data-stu-id="1d343-161">Download and unzip *docfx.zip* from [DocFX releases](https://github.com/dotnet/docfx/releases).</span></span>
* <span data-ttu-id="1d343-162">將 DocFX 新增至您的 PATH。</span><span class="sxs-lookup"><span data-stu-id="1d343-162">Add DocFX to your PATH.</span></span>
* <span data-ttu-id="1d343-163">在命令列視窗中，巡覽至包含 *docfx.json* 檔案的適當資料夾 (若是 ASP.NET 內容則為 *aspnet*；若是 ASP.NET Core 內容則為 *aspnetcore*)，然後執行下列命令：</span><span class="sxs-lookup"><span data-stu-id="1d343-163">In a command-line window, navigate to the appropriate folder that contains the *docfx.json* file (*aspnet* for ASP.NET content or *aspnetcore* for ASP.NET Core content) and run the following command:</span></span>

  ```
  docfx --serve
  ```
    
* <span data-ttu-id="1d343-164">在瀏覽器中，巡覽至 `http://localhost:8080`。</span><span class="sxs-lookup"><span data-stu-id="1d343-164">In a browser, navigate to `http://localhost:8080`.</span></span>

### <a name="mono-instructions"></a><span data-ttu-id="1d343-165">Mono 指示</span><span class="sxs-lookup"><span data-stu-id="1d343-165">Mono instructions</span></span>

* <span data-ttu-id="1d343-166">透過 Homebrew 安裝 Mono：`brew install mono`。</span><span class="sxs-lookup"><span data-stu-id="1d343-166">Install Mono via Homebrew: `brew install mono`.</span></span>
* <span data-ttu-id="1d343-167">下載[最新版本的 DocFX](https://github.com/dotnet/docfx/releases)。</span><span class="sxs-lookup"><span data-stu-id="1d343-167">Download the [latest version of DocFX](https://github.com/dotnet/docfx/releases).</span></span>
* <span data-ttu-id="1d343-168">解壓縮至 `\bin\docfx`。</span><span class="sxs-lookup"><span data-stu-id="1d343-168">Extract to `\bin\docfx`.</span></span>
* <span data-ttu-id="1d343-169">建立 **docfx** 的別名：</span><span class="sxs-lookup"><span data-stu-id="1d343-169">Create an alias for **docfx**:</span></span>

  ```
  function docfx {
    mono $HOME/bin/docfx/docfx.exe
  }
    
  function docfx-serve {
    mono $HOME/bin/docfx/docfx.exe serve _site
  }
  ```

* <span data-ttu-id="1d343-170">執行 *Docs\aspnet* 或 *Docs\aspnetcore* 目錄中的 `docfx` 來建置網站。</span><span class="sxs-lookup"><span data-stu-id="1d343-170">Run `docfx` in the *Docs\aspnet* or *Docs\aspnetcore* directory to build the site.</span></span> <span data-ttu-id="1d343-171">執行 `docfx-serve` 以檢視位於 `http://localhost:8080` 的網站。</span><span class="sxs-lookup"><span data-stu-id="1d343-171">Run `docfx-serve` to view the site at `http://localhost:8080`.</span></span>

## <a name="voice-and-tone"></a><span data-ttu-id="1d343-172">語態和語氣</span><span class="sxs-lookup"><span data-stu-id="1d343-172">Voice and tone</span></span>

<span data-ttu-id="1d343-173">我們撰寫文件的目標是盡可能讓越多使用者輕鬆了解越好。</span><span class="sxs-lookup"><span data-stu-id="1d343-173">Our goal is to write documentation that is easily understandable by the widest possible audience.</span></span> <span data-ttu-id="1d343-174">為此，我們制定了書寫樣式方針，並要求參與者務必遵循。</span><span class="sxs-lookup"><span data-stu-id="1d343-174">To that end, we established guidelines for writing style that we ask our contributors to follow.</span></span> <span data-ttu-id="1d343-175">如需詳細資訊，請參閱 .NET 存放庫中的 [Voice and tone guidelines](https://github.com/dotnet/docs/blob/master/styleguide/voice-tone.md) (語態和語氣方針)。</span><span class="sxs-lookup"><span data-stu-id="1d343-175">For more information, see [Voice and tone guidelines](https://github.com/dotnet/docs/blob/master/styleguide/voice-tone.md) in the .NET repo.</span></span>

## <a name="microsoft-writing-style-guide"></a><span data-ttu-id="1d343-176">Microsoft 書寫樣式指南</span><span class="sxs-lookup"><span data-stu-id="1d343-176">Microsoft Writing Style Guide</span></span>

<span data-ttu-id="1d343-177">[Microsoft Writing Style Guide](https://docs.microsoft.com/style-guide/welcome/) (Microsoft 書寫樣式指南) 針對所有形式的技術通訊提供書寫樣式和術語指引，包括 ASP.NET Core 文件。</span><span class="sxs-lookup"><span data-stu-id="1d343-177">The [Microsoft Writing Style Guide](https://docs.microsoft.com/style-guide/welcome/) provides writing style and terminology guidance for all forms of technology communication, including the ASP.NET Core documentation.</span></span>

## <a name="redirects"></a><span data-ttu-id="1d343-178">重新導向</span><span class="sxs-lookup"><span data-stu-id="1d343-178">Redirects</span></span>

<span data-ttu-id="1d343-179">如果您刪除文章、變更其檔案名稱，或把文章移至其他資料夾，請建立重新導向，確保將文章加入書籤的人員不會收到 *404 找不到*錯誤。</span><span class="sxs-lookup"><span data-stu-id="1d343-179">If you delete an article, change its file name, or move it to a different folder, create a redirect so that people who bookmarked the article don't receive a *404 Not Found* error.</span></span> <span data-ttu-id="1d343-180">將重新導向新增至[主要重新導向檔案](https://github.com/aspnet/Docs/blob/master/.openpublishing.redirection.json)。</span><span class="sxs-lookup"><span data-stu-id="1d343-180">Add redirects to the [master redirect file](https://github.com/aspnet/Docs/blob/master/.openpublishing.redirection.json).</span></span>