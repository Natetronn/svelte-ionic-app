<svelte:head>
  <title>Ionic UI Companion App - Fabs</title>
</svelte:head>

<ion-header translucent>
  <ion-toolbar>
    <ion-buttons slot="start">
      <ion-menu-button />
    </ion-buttons>
    <ion-title>Fab</ion-title>
  </ion-toolbar>
</ion-header>

<ion-content fullscreen class="ion-padding">
  <ion-fab horizontal="end" vertical="top" slot="fixed" edge>
    <ion-fab-button>
      <ion-icon name="add" />
    </ion-fab-button>
    <ion-fab-list>
      <ion-fab-button color="light">
        <ion-icon name="logo-facebook" />
      </ion-fab-button>
      <ion-fab-button color="light">
        <ion-icon name="logo-twitter" />
      </ion-fab-button>
      <ion-fab-button color="light">
        <ion-icon name="logo-vimeo" />
      </ion-fab-button>
    </ion-fab-list>
  </ion-fab>

  <ion-fab horizontal="end" vertical="center" slot="fixed">
    <ion-fab-button color="danger">
      <ion-icon name="add" />
    </ion-fab-button>
  </ion-fab>

  <ion-fab horizontal="end" vertical="bottom" slot="fixed">
    <ion-fab-button color="light">
      <ion-icon name="arrow-dropleft" />
    </ion-fab-button>
    <ion-fab-list side="start">
      <ion-fab-button color="light">
        <ion-icon name="logo-facebook" />
      </ion-fab-button>
      <ion-fab-button color="light">
        <ion-icon name="logo-twitter" />
      </ion-fab-button>
      <ion-fab-button color="light">
        <ion-icon name="logo-vimeo" />
      </ion-fab-button>
    </ion-fab-list>
  </ion-fab>

  <ion-fab horizontal="start" vertical="bottom" slot="fixed">
    <ion-fab-button color="dark">
      <ion-icon name="arrow-dropup" />
    </ion-fab-button>
    <ion-fab-list side="top">
      <ion-fab-button color="light">
        <ion-icon name="logo-facebook" />
      </ion-fab-button>
      <ion-fab-button color="light">
        <ion-icon name="logo-twitter" />
      </ion-fab-button>
      <ion-fab-button color="light">
        <ion-icon name="logo-vimeo" />
      </ion-fab-button>
      <ion-fab-button color="light">
        <ion-icon name="logo-google" />
      </ion-fab-button>
    </ion-fab-list>
  </ion-fab>

  <ion-fab horizontal="start" vertical="top" slot="fixed">
    <ion-fab-button color="secondary">
      <ion-icon name="arrow-dropright" />
    </ion-fab-button>
    <ion-fab-list side="end">
      <ion-fab-button color="light">
        <ion-icon name="logo-facebook" />
      </ion-fab-button>
      <ion-fab-button color="light">
        <ion-icon name="logo-twitter" />
      </ion-fab-button>
      <ion-fab-button color="light">
        <ion-icon name="logo-vimeo" />
      </ion-fab-button>
      <ion-fab-button color="light">
        <ion-icon name="logo-google" />
      </ion-fab-button>
    </ion-fab-list>
  </ion-fab>

  <ion-fab horizontal="center" vertical="center" slot="fixed">
    <ion-fab-button color="light">
      <ion-icon name="share" />
    </ion-fab-button>
    <ion-fab-list side="top">
      <ion-fab-button color="primary">
        <ion-icon name="logo-vimeo" />
      </ion-fab-button>
    </ion-fab-list>
    <ion-fab-list side="end">
      <ion-fab-button color="dark">
        <ion-icon name="logo-twitter" />
      </ion-fab-button>
    </ion-fab-list>
    <ion-fab-list side="bottom">
      <ion-fab-button color="secondary">
        <ion-icon name="logo-facebook" />
      </ion-fab-button>
    </ion-fab-list>
    <ion-fab-list side="start">
      <ion-fab-button color="light">
        <ion-icon name="logo-google" />
      </ion-fab-button>
    </ion-fab-list>
  </ion-fab>
</ion-content>
