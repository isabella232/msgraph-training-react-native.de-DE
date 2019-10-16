<!-- markdownlint-disable MD002 MD041 -->

<span data-ttu-id="6e876-101">In dieser Übung erstellen Sie mithilfe des Azure Active Directory Admin Center eine neue Azure AD systemeigene Anwendung.</span><span class="sxs-lookup"><span data-stu-id="6e876-101">In this exercise you will create a new Azure AD native application using the Azure Active Directory admin center.</span></span>

1. <span data-ttu-id="6e876-102">Öffnen Sie einen Browser, und navigieren Sie zum [Azure Active Directory Admin Center](https://aad.portal.azure.com). Melden Sie sich mit einem **persönlichen Konto** (auch: Microsoft-Konto) oder einem **Geschäfts- oder Schulkonto** an.</span><span class="sxs-lookup"><span data-stu-id="6e876-102">Open a browser and navigate to the [Azure Active Directory admin center](https://aad.portal.azure.com) and login using a **personal account** (aka: Microsoft Account) or **Work or School Account**.</span></span>

1. <span data-ttu-id="6e876-103">Wählen Sie in der linken Navigationsleiste **Azure Active Directory** aus, und wählen Sie dann **App-Registrierungen** unter **Manage**aus.</span><span class="sxs-lookup"><span data-stu-id="6e876-103">Select **Azure Active Directory** in the left-hand navigation, then select **App registrations** under **Manage**.</span></span>

    ![<span data-ttu-id="6e876-104">Ein Screenshot der APP-Registrierungen</span><span class="sxs-lookup"><span data-stu-id="6e876-104">A screenshot of the App registrations</span></span> ](./images/aad-portal-app-registrations.png)

1. <span data-ttu-id="6e876-105">Wählen Sie **Neue Registrierung** aus.</span><span class="sxs-lookup"><span data-stu-id="6e876-105">Select **New registration**.</span></span> <span data-ttu-id="6e876-106">Legen Sie auf der Seite **Anwendung registrieren** die Werte wie folgt fest.</span><span class="sxs-lookup"><span data-stu-id="6e876-106">On the **Register an application** page, set the values as follows.</span></span>

    - <span data-ttu-id="6e876-107">Legen Sie **Name** auf `React Native Graph Tutorial` fest.</span><span class="sxs-lookup"><span data-stu-id="6e876-107">Set **Name** to `React Native Graph Tutorial`.</span></span>
    - <span data-ttu-id="6e876-108">Legen Sie **Unterstützte Kontotypen** auf **Konten in allen Organisationsverzeichnissen und persönliche Microsoft-Konten** fest.</span><span class="sxs-lookup"><span data-stu-id="6e876-108">Set **Supported account types** to **Accounts in any organizational directory and personal Microsoft accounts**.</span></span>
    - <span data-ttu-id="6e876-109">Ändern Sie unter **Umleitungs-URI**das Dropdown-Menü auf **Public Client (Mobile #a0 Desktop)**, `graph-tutorial://react-native-auth`und legen Sie den Wert auf fest.</span><span class="sxs-lookup"><span data-stu-id="6e876-109">Under **Redirect URI**, change the dropdown to **Public client (mobile & desktop)**, and set the value to `graph-tutorial://react-native-auth`.</span></span>

    ![Screenshot der Seite "Anwendung registrieren"](./images/aad-register-an-app.png)

1. <span data-ttu-id="6e876-111">Wählen Sie **registrieren**aus.</span><span class="sxs-lookup"><span data-stu-id="6e876-111">Select **Register**.</span></span> <span data-ttu-id="6e876-112">Kopieren Sie auf der Seite **systemeigene Graph-Lernprogramm reagieren** den Wert der **Anwendungs-ID (Client)** , und speichern Sie Sie, um Sie im nächsten Schritt zu benötigen.</span><span class="sxs-lookup"><span data-stu-id="6e876-112">On the **React Native Graph Tutorial** page, copy the value of the **Application (client) ID** and save it, you will need it in the next step.</span></span>

    ![Ein Screenshot der Anwendungs-ID der neuen App-Registrierung](./images/aad-application-id.png)

1. <span data-ttu-id="6e876-114">Wählen Sie unter **Verwalten**die Option **Authentifizierung**aus.</span><span class="sxs-lookup"><span data-stu-id="6e876-114">Under **Manage**, select **Authentication**.</span></span> <span data-ttu-id="6e876-115">Fügen Sie auf der Seite " **Umleitungs-URIs** " einen weiteren Umleitungs-URI vom Typ " **Public Client" (Mobile #a0 Desktop)** mit dem URI `urn:ietf:wg:oauth:2.0:oob`hinzu.</span><span class="sxs-lookup"><span data-stu-id="6e876-115">On the **Redirect URIs** page, add another redirect URI of type **Public client (mobile & desktop)**, with the URI `urn:ietf:wg:oauth:2.0:oob`.</span></span> <span data-ttu-id="6e876-116">Klicken Sie auf **Speichern**.</span><span class="sxs-lookup"><span data-stu-id="6e876-116">Select **Save**.</span></span>

    ![Screenshot der Seite "Umleitungs-URIs"](./images/aad-redirect-uris.png)
