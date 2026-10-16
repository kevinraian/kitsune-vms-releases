# Avisos de terceiros

O Kitsune VMS é distribuído sob a licença MIT (veja `LICENSE`) e usa os componentes abaixo, cada um sob a sua própria licença.

| Componente | Uso | Licença | Fonte |
|---|---|---|---|
| libVLC (VideoLAN.LibVLC.Windows 3.0) | Decodificação e reprodução de vídeo | LGPL-2.1-or-later | https://www.videolan.org/vlc/ |
| LibVLCSharp | Ligação .NET para o libVLC | LGPL-2.1-or-later | https://github.com/videolan/libvlcsharp |
| DirectShowLib.Standard | Enumeração de webcams | LGPL-2.1 | https://github.com/dotnet/DirectShowLib |
| Onvif.Core | Cliente ONVIF (perfis, PTZ) | MIT | https://github.com/Jazea/Onvif.Core |
| ONNX Runtime (DirectML) | Execução do modelo de detecção de objetos | MIT | https://github.com/microsoft/onnxruntime |
| YOLOX-S (Megvii) | Modelo de detecção de objetos (`yolox_s.onnx`) | Apache-2.0 | https://github.com/Megvii-BaseDetection/YOLOX |
| CommunityToolkit.Mvvm | Padrão MVVM | MIT | https://github.com/CommunityToolkit/dotnet |
| Microsoft.Extensions.* | Injeção de dependência e hospedagem | MIT | https://github.com/dotnet/runtime |
| Microsoft.Toolkit.Uwp.Notifications | Notificações do Windows | MIT | https://github.com/CommunityToolkit/WindowsCommunityToolkit |
| Velopack | Instalador e atualizações automáticas | MIT | https://github.com/velopack/velopack |
| Material.Icons.WPF | Ícones da interface | MIT (ícones: Apache-2.0) | https://github.com/SKProCH/Material.Icons |
| .NET 8 / WPF | Plataforma | MIT | https://github.com/dotnet/wpf |

## Bibliotecas LGPL

O libVLC, o LibVLCSharp e o DirectShowLib são distribuídos como DLLs separadas (ligação dinâmica) e sem modificações. Você pode substituí-las por versões próprias colocando as DLLs equivalentes na pasta do aplicativo. O código-fonte delas está nos endereços da tabela. O texto completo da LGPL-2.1 está em https://www.gnu.org/licenses/old-licenses/lgpl-2.1.html.

## Marcas

VLC é marca da VideoLAN. ONVIF é marca da ONVIF, Inc. Este projeto não é afiliado a nenhuma das duas.
