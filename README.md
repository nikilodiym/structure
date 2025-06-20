# structure

C:.
│   .gitignore
│   CinemaHub.sln
│   CinemaHub.sln.DotSettings.user
│   README.md
│   structure.txt
│   
├───.idea
│   └───.idea.CinemaHub
│       └───.idea
│               .gitignore
│               encodings.xml
│               indexLayout.xml
│               projectSettingsUpdater.xml
│               vcs.xml
│               workspace.xml
│               
├───CinemaServer
│   │   CinemaServer.csproj
│   │   
│   ├───bin
│   │   └───Debug
│   │       └───net8.0
│   │               CinemaServer.deps.json
│   │               CinemaServer.dll
│   │               CinemaServer.pdb
│   │               Core.dll
│   │               Core.pdb
│   │               Services.dll
│   │               Services.pdb
│   │               
│   ├───CinemaSupabase
│   │       SupabaseAuthDataProvider.cs
│   │       SupabaseClient.cs
│   │       
│   ├───Controllers
│   │       AuthController.cs
│   │       FilmController.cs
│   │       
│   ├───DTOs
│   │   │   BookingDto.cs
│   │   │   FilmDto.cs
│   │   │   
│   │   └───Auth
│   │           LoginRequestDto.cs
│   │           LoginResponseDto.cs
│   │           RegisterRequestDto.cs
│   │           RegisterResponseDto.cs
│   │           
│   ├───Exceptions
│   │       FilmNotFoundException.cs
│   │       SeatAlreadyBookedException.cs
│   │       
│   ├───Models
│   │       Movie.cs
│   │       Reservation.cs
│   │       User.cs
│   │       
│   ├───obj
│   │   │   CinemaServer.csproj.nuget.dgspec.json
│   │   │   CinemaServer.csproj.nuget.g.props
│   │   │   CinemaServer.csproj.nuget.g.targets
│   │   │   project.assets.json
│   │   │   project.nuget.cache
│   │   │   project.packagespec.json
│   │   │   rider.project.model.nuget.info
│   │   │   rider.project.restore.info
│   │   │   
│   │   └───Debug
│   │       └───net8.0
│   │           │   .NETCoreApp,Version=v8.0.AssemblyAttributes.cs
│   │           │   CinemaSe.9AC22F6F.Up2Date
│   │           │   CinemaServer.AssemblyInfo.cs
│   │           │   CinemaServer.AssemblyInfoInputs.cache
│   │           │   CinemaServer.assets.cache
│   │           │   CinemaServer.csproj.AssemblyReference.cache
│   │           │   CinemaServer.csproj.CoreCompileInputs.cache
│   │           │   CinemaServer.csproj.FileListAbsolute.txt
│   │           │   CinemaServer.dll
│   │           │   CinemaServer.GeneratedMSBuildEditorConfig.editorconfig
│   │           │   CinemaServer.GlobalUsings.g.cs
│   │           │   CinemaServer.pdb
│   │           │   CinemaServer.sourcelink.json
│   │           │   
│   │           ├───ref
│   │           │       CinemaServer.dll
│   │           │       
│   │           └───refint
│   │                   CinemaServer.dll
│   │                   
│   └───Services
│           MovieService.cs
│           
├───CinemaWPF
│   │   App.xaml
│   │   App.xaml.cs
│   │   AssemblyInfo.cs
│   │   CinemaWPF.csproj
│   │   
│   ├───Assets
│   │       cinem.jfif
│   │       cinnnema.jpg
│   │       convertedCinemaImage.png
│   │       
│   ├───bin
│   │   └───Debug
│   │       └───net8.0-windows
│   │               CinemaServer.dll
│   │               CinemaServer.pdb
│   │               CinemaWPF.deps.json
│   │               CinemaWPF.dll
│   │               CinemaWPF.exe
│   │               CinemaWPF.pdb
│   │               CinemaWPF.runtimeconfig.json
│   │               Core.dll
│   │               Core.pdb
│   │               MaterialDesignColors.dll
│   │               MaterialDesignThemes.Wpf.dll
│   │               Microsoft.AspNetCore.Authentication.Abstractions.dll
│   │               Microsoft.AspNetCore.Authentication.Core.dll
│   │               Microsoft.AspNetCore.Authorization.dll
│   │               Microsoft.AspNetCore.Authorization.Policy.dll
│   │               Microsoft.AspNetCore.Hosting.Abstractions.dll
│   │               Microsoft.AspNetCore.Hosting.Server.Abstractions.dll
│   │               Microsoft.AspNetCore.Http.Abstractions.dll
│   │               Microsoft.AspNetCore.Http.dll
│   │               Microsoft.AspNetCore.Http.Extensions.dll
│   │               Microsoft.AspNetCore.Http.Features.dll
│   │               Microsoft.AspNetCore.Mvc.Abstractions.dll
│   │               Microsoft.AspNetCore.Mvc.Core.dll
│   │               Microsoft.AspNetCore.ResponseCaching.Abstractions.dll
│   │               Microsoft.AspNetCore.Routing.Abstractions.dll
│   │               Microsoft.AspNetCore.Routing.dll
│   │               Microsoft.AspNetCore.WebUtilities.dll
│   │               Microsoft.DotNet.PlatformAbstractions.dll
│   │               Microsoft.Extensions.Configuration.Abstractions.dll
│   │               Microsoft.Extensions.Configuration.dll
│   │               Microsoft.Extensions.DependencyInjection.Abstractions.dll
│   │               Microsoft.Extensions.DependencyInjection.dll
│   │               Microsoft.Extensions.DependencyModel.dll
│   │               Microsoft.Extensions.Diagnostics.Abstractions.dll
│   │               Microsoft.Extensions.FileProviders.Abstractions.dll
│   │               Microsoft.Extensions.Hosting.Abstractions.dll
│   │               Microsoft.Extensions.Logging.Abstractions.dll
│   │               Microsoft.Extensions.ObjectPool.dll
│   │               Microsoft.Extensions.Options.dll
│   │               Microsoft.Extensions.Primitives.dll
│   │               Microsoft.IdentityModel.Abstractions.dll
│   │               Microsoft.IdentityModel.JsonWebTokens.dll
│   │               Microsoft.IdentityModel.Logging.dll
│   │               Microsoft.IdentityModel.Tokens.dll
│   │               Microsoft.IO.RecyclableMemoryStream.dll
│   │               Microsoft.Net.Http.Headers.dll
│   │               Microsoft.Xaml.Behaviors.dll
│   │               MimeMapping.dll
│   │               Newtonsoft.Json.dll
│   │               Services.dll
│   │               Services.pdb
│   │               Supabase.Core.dll
│   │               Supabase.dll
│   │               Supabase.Functions.dll
│   │               Supabase.Gotrue.dll
│   │               Supabase.Postgrest.dll
│   │               Supabase.Realtime.dll
│   │               Supabase.Storage.dll
│   │               System.IdentityModel.Tokens.Jwt.dll
│   │               System.Reactive.dll
│   │               Websocket.Client.dll
│   │               
│   ├───Controls
│   │       RatingControl.xaml
│   │       RatingControl.xaml.cs
│   │       SeatControl.xaml
│   │       SeatControl.xaml.cs
│   │       
│   ├───Converters
│   │       BoolToVisibilityConverter.cs
│   │       DateTimeToFilmFormat.cs
│   │       StringNullOrEmptyToVisibilityConverter.cs
│   │       ZeroToVisibilityConverter.cs
│   │       
│   ├───Models
│   │       User.cs
│   │       
│   ├───obj
│   │   │   CinemaWPF.csproj.nuget.dgspec.json
│   │   │   CinemaWPF.csproj.nuget.g.props
│   │   │   CinemaWPF.csproj.nuget.g.targets
│   │   │   CinemaWPF_f4321wz5_wpftmp.csproj.nuget.dgspec.json
│   │   │   CinemaWPF_f4321wz5_wpftmp.csproj.nuget.g.props
│   │   │   CinemaWPF_f4321wz5_wpftmp.csproj.nuget.g.targets
│   │   │   CinemaWPF_lemhit3u_wpftmp.csproj.nuget.dgspec.json
│   │   │   CinemaWPF_lemhit3u_wpftmp.csproj.nuget.g.props
│   │   │   CinemaWPF_lemhit3u_wpftmp.csproj.nuget.g.targets
│   │   │   CinemaWPF_pkdnaph3_wpftmp.csproj.nuget.dgspec.json
│   │   │   CinemaWPF_pkdnaph3_wpftmp.csproj.nuget.g.props
│   │   │   CinemaWPF_pkdnaph3_wpftmp.csproj.nuget.g.targets
│   │   │   CinemaWPF_s5pezkwn_wpftmp.csproj.nuget.dgspec.json
│   │   │   CinemaWPF_s5pezkwn_wpftmp.csproj.nuget.g.props
│   │   │   CinemaWPF_s5pezkwn_wpftmp.csproj.nuget.g.targets
│   │   │   CinemaWPF_x23a54wz_wpftmp.csproj.nuget.dgspec.json
│   │   │   CinemaWPF_x23a54wz_wpftmp.csproj.nuget.g.props
│   │   │   CinemaWPF_x23a54wz_wpftmp.csproj.nuget.g.targets
│   │   │   project.assets.json
│   │   │   project.nuget.cache
│   │   │   project.packagespec.json
│   │   │   rider.project.model.nuget.info
│   │   │   rider.project.restore.info
│   │   │   
│   │   └───Debug
│   │       └───net8.0-windows
│   │           │   .NETCoreApp,Version=v8.0.AssemblyAttributes.cs
│   │           │   App.baml
│   │           │   App.g.cs
│   │           │   apphost.exe
│   │           │   CinemaWPF.AssemblyInfo.cs
│   │           │   CinemaWPF.AssemblyInfoInputs.cache
│   │           │   CinemaWPF.assets.cache
│   │           │   CinemaWPF.csproj.AssemblyReference.cache
│   │           │   CinemaWPF.csproj.CoreCompileInputs.cache
│   │           │   CinemaWPF.csproj.FileListAbsolute.txt
│   │           │   CinemaWPF.csproj.Up2Date
│   │           │   CinemaWPF.dll
│   │           │   CinemaWPF.g.resources
│   │           │   CinemaWPF.GeneratedMSBuildEditorConfig.editorconfig
│   │           │   CinemaWPF.genruntimeconfig.cache
│   │           │   CinemaWPF.GlobalUsings.g.cs
│   │           │   CinemaWPF.pdb
│   │           │   CinemaWPF.sourcelink.json
│   │           │   CinemaWPF_0qrxgrqi_wpftmp.AssemblyInfo.cs
│   │           │   CinemaWPF_0qrxgrqi_wpftmp.AssemblyInfoInputs.cache
│   │           │   CinemaWPF_0qrxgrqi_wpftmp.assets.cache
│   │           │   CinemaWPF_0qrxgrqi_wpftmp.GeneratedMSBuildEditorConfig.editorconfig
│   │           │   CinemaWPF_0qrxgrqi_wpftmp.GlobalUsings.g.cs
│   │           │   CinemaWPF_0qrxgrqi_wpftmp.sourcelink.json
│   │           │   CinemaWPF_2aiox042_wpftmp.AssemblyInfo.cs
│   │           │   CinemaWPF_2aiox042_wpftmp.AssemblyInfoInputs.cache
│   │           │   CinemaWPF_2aiox042_wpftmp.assets.cache
│   │           │   CinemaWPF_2aiox042_wpftmp.GeneratedMSBuildEditorConfig.editorconfig
│   │           │   CinemaWPF_2aiox042_wpftmp.GlobalUsings.g.cs
│   │           │   CinemaWPF_2aiox042_wpftmp.sourcelink.json
│   │           │   CinemaWPF_2x1uk0e5_wpftmp.AssemblyInfo.cs
│   │           │   CinemaWPF_2x1uk0e5_wpftmp.AssemblyInfoInputs.cache
│   │           │   CinemaWPF_2x1uk0e5_wpftmp.assets.cache
│   │           │   CinemaWPF_2x1uk0e5_wpftmp.GeneratedMSBuildEditorConfig.editorconfig
│   │           │   CinemaWPF_2x1uk0e5_wpftmp.GlobalUsings.g.cs
│   │           │   CinemaWPF_2x1uk0e5_wpftmp.sourcelink.json
│   │           │   CinemaWPF_3wurps2g_wpftmp.AssemblyInfo.cs
│   │           │   CinemaWPF_3wurps2g_wpftmp.AssemblyInfoInputs.cache
│   │           │   CinemaWPF_3wurps2g_wpftmp.assets.cache
│   │           │   CinemaWPF_3wurps2g_wpftmp.GeneratedMSBuildEditorConfig.editorconfig
│   │           │   CinemaWPF_3wurps2g_wpftmp.GlobalUsings.g.cs
│   │           │   CinemaWPF_3wurps2g_wpftmp.sourcelink.json
│   │           │   CinemaWPF_3yis54hy_wpftmp.AssemblyInfo.cs
│   │           │   CinemaWPF_3yis54hy_wpftmp.AssemblyInfoInputs.cache
│   │           │   CinemaWPF_3yis54hy_wpftmp.assets.cache
│   │           │   CinemaWPF_3yis54hy_wpftmp.GeneratedMSBuildEditorConfig.editorconfig
│   │           │   CinemaWPF_3yis54hy_wpftmp.GlobalUsings.g.cs
│   │           │   CinemaWPF_3yis54hy_wpftmp.sourcelink.json
│   │           │   CinemaWPF_4zl3boaz_wpftmp.AssemblyInfo.cs
│   │           │   CinemaWPF_4zl3boaz_wpftmp.AssemblyInfoInputs.cache
│   │           │   CinemaWPF_4zl3boaz_wpftmp.assets.cache
│   │           │   CinemaWPF_4zl3boaz_wpftmp.GeneratedMSBuildEditorConfig.editorconfig
│   │           │   CinemaWPF_4zl3boaz_wpftmp.GlobalUsings.g.cs
│   │           │   CinemaWPF_4zl3boaz_wpftmp.sourcelink.json
│   │           │   CinemaWPF_5fxqnl0g_wpftmp.AssemblyInfo.cs
│   │           │   CinemaWPF_5fxqnl0g_wpftmp.AssemblyInfoInputs.cache
│   │           │   CinemaWPF_5fxqnl0g_wpftmp.assets.cache
│   │           │   CinemaWPF_5fxqnl0g_wpftmp.GeneratedMSBuildEditorConfig.editorconfig
│   │           │   CinemaWPF_5fxqnl0g_wpftmp.GlobalUsings.g.cs
│   │           │   CinemaWPF_5fxqnl0g_wpftmp.sourcelink.json
│   │           │   CinemaWPF_5muf0t0e_wpftmp.AssemblyInfo.cs
│   │           │   CinemaWPF_5muf0t0e_wpftmp.AssemblyInfoInputs.cache
│   │           │   CinemaWPF_5muf0t0e_wpftmp.assets.cache
│   │           │   CinemaWPF_5muf0t0e_wpftmp.GeneratedMSBuildEditorConfig.editorconfig
│   │           │   CinemaWPF_5muf0t0e_wpftmp.GlobalUsings.g.cs
│   │           │   CinemaWPF_5muf0t0e_wpftmp.sourcelink.json
│   │           │   CinemaWPF_b2alqop2_wpftmp.AssemblyInfo.cs
│   │           │   CinemaWPF_b2alqop2_wpftmp.AssemblyInfoInputs.cache
│   │           │   CinemaWPF_b2alqop2_wpftmp.assets.cache
│   │           │   CinemaWPF_b2alqop2_wpftmp.GeneratedMSBuildEditorConfig.editorconfig
│   │           │   CinemaWPF_b2alqop2_wpftmp.GlobalUsings.g.cs
│   │           │   CinemaWPF_b2alqop2_wpftmp.sourcelink.json
│   │           │   CinemaWPF_bhjxtyxi_wpftmp.AssemblyInfo.cs
│   │           │   CinemaWPF_bhjxtyxi_wpftmp.AssemblyInfoInputs.cache
│   │           │   CinemaWPF_bhjxtyxi_wpftmp.assets.cache
│   │           │   CinemaWPF_bhjxtyxi_wpftmp.GeneratedMSBuildEditorConfig.editorconfig
│   │           │   CinemaWPF_bhjxtyxi_wpftmp.GlobalUsings.g.cs
│   │           │   CinemaWPF_bhjxtyxi_wpftmp.sourcelink.json
│   │           │   CinemaWPF_c1d25v5n_wpftmp.AssemblyInfo.cs
│   │           │   CinemaWPF_c1d25v5n_wpftmp.AssemblyInfoInputs.cache
│   │           │   CinemaWPF_c1d25v5n_wpftmp.assets.cache
│   │           │   CinemaWPF_c1d25v5n_wpftmp.GeneratedMSBuildEditorConfig.editorconfig
│   │           │   CinemaWPF_c1d25v5n_wpftmp.GlobalUsings.g.cs
│   │           │   CinemaWPF_c1d25v5n_wpftmp.sourcelink.json
│   │           │   CinemaWPF_e21grkqq_wpftmp.AssemblyInfo.cs
│   │           │   CinemaWPF_e21grkqq_wpftmp.AssemblyInfoInputs.cache
│   │           │   CinemaWPF_e21grkqq_wpftmp.assets.cache
│   │           │   CinemaWPF_e21grkqq_wpftmp.GeneratedMSBuildEditorConfig.editorconfig
│   │           │   CinemaWPF_e21grkqq_wpftmp.GlobalUsings.g.cs
│   │           │   CinemaWPF_e21grkqq_wpftmp.sourcelink.json
│   │           │   CinemaWPF_f4321wz5_wpftmp.AssemblyInfo.cs
│   │           │   CinemaWPF_f4321wz5_wpftmp.AssemblyInfoInputs.cache
│   │           │   CinemaWPF_f4321wz5_wpftmp.assets.cache
│   │           │   CinemaWPF_f4321wz5_wpftmp.GeneratedMSBuildEditorConfig.editorconfig
│   │           │   CinemaWPF_f4321wz5_wpftmp.GlobalUsings.g.cs
│   │           │   CinemaWPF_f4321wz5_wpftmp.sourcelink.json
│   │           │   CinemaWPF_fenft1wb_wpftmp.AssemblyInfo.cs
│   │           │   CinemaWPF_fenft1wb_wpftmp.AssemblyInfoInputs.cache
│   │           │   CinemaWPF_fenft1wb_wpftmp.assets.cache
│   │           │   CinemaWPF_fenft1wb_wpftmp.GeneratedMSBuildEditorConfig.editorconfig
│   │           │   CinemaWPF_fenft1wb_wpftmp.GlobalUsings.g.cs
│   │           │   CinemaWPF_fenft1wb_wpftmp.sourcelink.json
│   │           │   CinemaWPF_fzol2odz_wpftmp.AssemblyInfo.cs
│   │           │   CinemaWPF_fzol2odz_wpftmp.AssemblyInfoInputs.cache
│   │           │   CinemaWPF_fzol2odz_wpftmp.assets.cache
│   │           │   CinemaWPF_fzol2odz_wpftmp.GeneratedMSBuildEditorConfig.editorconfig
│   │           │   CinemaWPF_fzol2odz_wpftmp.GlobalUsings.g.cs
│   │           │   CinemaWPF_fzol2odz_wpftmp.sourcelink.json
│   │           │   CinemaWPF_lemhit3u_wpftmp.AssemblyInfo.cs
│   │           │   CinemaWPF_lemhit3u_wpftmp.AssemblyInfoInputs.cache
│   │           │   CinemaWPF_lemhit3u_wpftmp.assets.cache
│   │           │   CinemaWPF_lemhit3u_wpftmp.GeneratedMSBuildEditorConfig.editorconfig
│   │           │   CinemaWPF_lemhit3u_wpftmp.GlobalUsings.g.cs
│   │           │   CinemaWPF_lemhit3u_wpftmp.sourcelink.json
│   │           │   CinemaWPF_ln2tew03_wpftmp.AssemblyInfo.cs
│   │           │   CinemaWPF_ln2tew03_wpftmp.AssemblyInfoInputs.cache
│   │           │   CinemaWPF_ln2tew03_wpftmp.assets.cache
│   │           │   CinemaWPF_ln2tew03_wpftmp.GeneratedMSBuildEditorConfig.editorconfig
│   │           │   CinemaWPF_ln2tew03_wpftmp.GlobalUsings.g.cs
│   │           │   CinemaWPF_ln2tew03_wpftmp.sourcelink.json
│   │           │   CinemaWPF_MarkupCompile.cache
│   │           │   CinemaWPF_MarkupCompile.lref
│   │           │   CinemaWPF_mlkgxf0u_wpftmp.AssemblyInfo.cs
│   │           │   CinemaWPF_mlkgxf0u_wpftmp.AssemblyInfoInputs.cache
│   │           │   CinemaWPF_mlkgxf0u_wpftmp.assets.cache
│   │           │   CinemaWPF_mlkgxf0u_wpftmp.GeneratedMSBuildEditorConfig.editorconfig
│   │           │   CinemaWPF_mlkgxf0u_wpftmp.GlobalUsings.g.cs
│   │           │   CinemaWPF_mlkgxf0u_wpftmp.sourcelink.json
│   │           │   CinemaWPF_nvlibvg2_wpftmp.AssemblyInfo.cs
│   │           │   CinemaWPF_nvlibvg2_wpftmp.AssemblyInfoInputs.cache
│   │           │   CinemaWPF_nvlibvg2_wpftmp.assets.cache
│   │           │   CinemaWPF_nvlibvg2_wpftmp.GeneratedMSBuildEditorConfig.editorconfig
│   │           │   CinemaWPF_nvlibvg2_wpftmp.GlobalUsings.g.cs
│   │           │   CinemaWPF_nvlibvg2_wpftmp.sourcelink.json
│   │           │   CinemaWPF_oqmxwou1_wpftmp.AssemblyInfo.cs
│   │           │   CinemaWPF_oqmxwou1_wpftmp.AssemblyInfoInputs.cache
│   │           │   CinemaWPF_oqmxwou1_wpftmp.assets.cache
│   │           │   CinemaWPF_oqmxwou1_wpftmp.GeneratedMSBuildEditorConfig.editorconfig
│   │           │   CinemaWPF_oqmxwou1_wpftmp.GlobalUsings.g.cs
│   │           │   CinemaWPF_oqmxwou1_wpftmp.sourcelink.json
│   │           │   CinemaWPF_pkdnaph3_wpftmp.AssemblyInfo.cs
│   │           │   CinemaWPF_pkdnaph3_wpftmp.AssemblyInfoInputs.cache
│   │           │   CinemaWPF_pkdnaph3_wpftmp.assets.cache
│   │           │   CinemaWPF_pkdnaph3_wpftmp.GeneratedMSBuildEditorConfig.editorconfig
│   │           │   CinemaWPF_pkdnaph3_wpftmp.GlobalUsings.g.cs
│   │           │   CinemaWPF_pkdnaph3_wpftmp.sourcelink.json
│   │           │   CinemaWPF_qk433zpp_wpftmp.AssemblyInfo.cs
│   │           │   CinemaWPF_qk433zpp_wpftmp.AssemblyInfoInputs.cache
│   │           │   CinemaWPF_qk433zpp_wpftmp.assets.cache
│   │           │   CinemaWPF_qk433zpp_wpftmp.GeneratedMSBuildEditorConfig.editorconfig
│   │           │   CinemaWPF_qk433zpp_wpftmp.GlobalUsings.g.cs
│   │           │   CinemaWPF_qk433zpp_wpftmp.sourcelink.json
│   │           │   CinemaWPF_s3zbqqoc_wpftmp.AssemblyInfo.cs
│   │           │   CinemaWPF_s3zbqqoc_wpftmp.AssemblyInfoInputs.cache
│   │           │   CinemaWPF_s3zbqqoc_wpftmp.assets.cache
│   │           │   CinemaWPF_s3zbqqoc_wpftmp.GeneratedMSBuildEditorConfig.editorconfig
│   │           │   CinemaWPF_s3zbqqoc_wpftmp.GlobalUsings.g.cs
│   │           │   CinemaWPF_s3zbqqoc_wpftmp.sourcelink.json
│   │           │   CinemaWPF_s5pezkwn_wpftmp.AssemblyInfo.cs
│   │           │   CinemaWPF_s5pezkwn_wpftmp.AssemblyInfoInputs.cache
│   │           │   CinemaWPF_s5pezkwn_wpftmp.assets.cache
│   │           │   CinemaWPF_s5pezkwn_wpftmp.GeneratedMSBuildEditorConfig.editorconfig
│   │           │   CinemaWPF_s5pezkwn_wpftmp.GlobalUsings.g.cs
│   │           │   CinemaWPF_s5pezkwn_wpftmp.sourcelink.json
│   │           │   CinemaWPF_sombkkoy_wpftmp.AssemblyInfo.cs
│   │           │   CinemaWPF_sombkkoy_wpftmp.AssemblyInfoInputs.cache
│   │           │   CinemaWPF_sombkkoy_wpftmp.assets.cache
│   │           │   CinemaWPF_sombkkoy_wpftmp.GeneratedMSBuildEditorConfig.editorconfig
│   │           │   CinemaWPF_sombkkoy_wpftmp.GlobalUsings.g.cs
│   │           │   CinemaWPF_sombkkoy_wpftmp.sourcelink.json
│   │           │   CinemaWPF_tjklzq51_wpftmp.AssemblyInfo.cs
│   │           │   CinemaWPF_tjklzq51_wpftmp.AssemblyInfoInputs.cache
│   │           │   CinemaWPF_tjklzq51_wpftmp.assets.cache
│   │           │   CinemaWPF_tjklzq51_wpftmp.GeneratedMSBuildEditorConfig.editorconfig
│   │           │   CinemaWPF_tjklzq51_wpftmp.GlobalUsings.g.cs
│   │           │   CinemaWPF_tjklzq51_wpftmp.sourcelink.json
│   │           │   CinemaWPF_ujmhoxmi_wpftmp.AssemblyInfo.cs
│   │           │   CinemaWPF_ujmhoxmi_wpftmp.AssemblyInfoInputs.cache
│   │           │   CinemaWPF_ujmhoxmi_wpftmp.assets.cache
│   │           │   CinemaWPF_ujmhoxmi_wpftmp.GeneratedMSBuildEditorConfig.editorconfig
│   │           │   CinemaWPF_ujmhoxmi_wpftmp.GlobalUsings.g.cs
│   │           │   CinemaWPF_ujmhoxmi_wpftmp.sourcelink.json
│   │           │   CinemaWPF_uk5oqi5k_wpftmp.AssemblyInfo.cs
│   │           │   CinemaWPF_uk5oqi5k_wpftmp.AssemblyInfoInputs.cache
│   │           │   CinemaWPF_uk5oqi5k_wpftmp.assets.cache
│   │           │   CinemaWPF_uk5oqi5k_wpftmp.GeneratedMSBuildEditorConfig.editorconfig
│   │           │   CinemaWPF_uk5oqi5k_wpftmp.GlobalUsings.g.cs
│   │           │   CinemaWPF_uk5oqi5k_wpftmp.sourcelink.json
│   │           │   CinemaWPF_um20atkm_wpftmp.AssemblyInfo.cs
│   │           │   CinemaWPF_um20atkm_wpftmp.AssemblyInfoInputs.cache
│   │           │   CinemaWPF_um20atkm_wpftmp.assets.cache
│   │           │   CinemaWPF_um20atkm_wpftmp.GeneratedMSBuildEditorConfig.editorconfig
│   │           │   CinemaWPF_um20atkm_wpftmp.GlobalUsings.g.cs
│   │           │   CinemaWPF_um20atkm_wpftmp.sourcelink.json
│   │           │   CinemaWPF_wq3103xn_wpftmp.AssemblyInfo.cs
│   │           │   CinemaWPF_wq3103xn_wpftmp.AssemblyInfoInputs.cache
│   │           │   CinemaWPF_wq3103xn_wpftmp.assets.cache
│   │           │   CinemaWPF_wq3103xn_wpftmp.GeneratedMSBuildEditorConfig.editorconfig
│   │           │   CinemaWPF_wq3103xn_wpftmp.GlobalUsings.g.cs
│   │           │   CinemaWPF_wq3103xn_wpftmp.sourcelink.json
│   │           │   CinemaWPF_x23a54wz_wpftmp.AssemblyInfo.cs
│   │           │   CinemaWPF_x23a54wz_wpftmp.AssemblyInfoInputs.cache
│   │           │   CinemaWPF_x23a54wz_wpftmp.assets.cache
│   │           │   CinemaWPF_x23a54wz_wpftmp.GeneratedMSBuildEditorConfig.editorconfig
│   │           │   CinemaWPF_x23a54wz_wpftmp.GlobalUsings.g.cs
│   │           │   CinemaWPF_x23a54wz_wpftmp.sourcelink.json
│   │           │   CinemaWPF_y4xuio5g_wpftmp.AssemblyInfo.cs
│   │           │   CinemaWPF_y4xuio5g_wpftmp.AssemblyInfoInputs.cache
│   │           │   CinemaWPF_y4xuio5g_wpftmp.assets.cache
│   │           │   CinemaWPF_y4xuio5g_wpftmp.GeneratedMSBuildEditorConfig.editorconfig
│   │           │   CinemaWPF_y4xuio5g_wpftmp.GlobalUsings.g.cs
│   │           │   CinemaWPF_y4xuio5g_wpftmp.sourcelink.json
│   │           │   CinemaWPF_yhfpdtoc_wpftmp.AssemblyInfo.cs
│   │           │   CinemaWPF_yhfpdtoc_wpftmp.AssemblyInfoInputs.cache
│   │           │   CinemaWPF_yhfpdtoc_wpftmp.assets.cache
│   │           │   CinemaWPF_yhfpdtoc_wpftmp.GeneratedMSBuildEditorConfig.editorconfig
│   │           │   CinemaWPF_yhfpdtoc_wpftmp.GlobalUsings.g.cs
│   │           │   CinemaWPF_yhfpdtoc_wpftmp.sourcelink.json
│   │           │   GeneratedInternalTypeHelper.g.cs
│   │           │   
│   │           ├───Controls
│   │           │       RatingControl.baml
│   │           │       RatingControl.g.cs
│   │           │       SeatControl.baml
│   │           │       SeatControl.g.cs
│   │           │       
│   │           ├───ref
│   │           │       CinemaWPF.dll
│   │           │       
│   │           ├───refint
│   │           │       CinemaWPF.dll
│   │           │       
│   │           ├───Resources
│   │           │   └───Styles
│   │           │           ButtonStyles.baml
│   │           │           ButtonStyles.g.cs
│   │           │           TextStyles.baml
│   │           │           TextStyles.g.cs
│   │           │           
│   │           └───Views
│   │               │   MainWindow.baml
│   │               │   MainWindow.g.cs
│   │               │   
│   │               ├───Auth
│   │               │       AdminLoginView.baml
│   │               │       AdminLoginView.g.cs
│   │               │       AdminWindow.baml
│   │               │       AdminWindow.g.cs
│   │               │       LoginView.baml
│   │               │       LoginView.g.cs
│   │               │       LoginWindowView.baml
│   │               │       LoginWindowView.g.cs
│   │               │       RegisterWindowView.baml
│   │               │       RegisterWindowView.g.cs
│   │               │       UserWindow.baml
│   │               │       UserWindow.g.cs
│   │               │       
│   │               ├───Booking
│   │               │       BookingView.baml
│   │               │       BookingView.g.cs
│   │               │       PaymentView.baml
│   │               │       PaymentView.g.cs
│   │               │       
│   │               ├───Films
│   │               │       FilmDetailsView.baml
│   │               │       FilmDetailsView.g.cs
│   │               │       FilmsView.baml
│   │               │       FilmsView.g.cs
│   │               │       
│   │               └───Schedule
│   │                       ScheduleView.baml
│   │                       ScheduleView.g.cs
│   │                       ScreeningDetailsView.baml
│   │                       ScreeningDetailsView.g.cs
│   │                       
│   ├───Resources
│   │   └───Styles
│   │           ButtonStyles.xaml
│   │           ButtonStyles.xaml.cs
│   │           TextStyles.xaml
│   │           TextStyles.xaml.cs
│   │           
│   ├───ViewModels
│   │   │   ViewModelLocator.cs
│   │   │   
│   │   ├───Admin
│   │   │       AdminDashboardViewModel.cs
│   │   │       FilmManagementViewModel.cs
│   │   │       UserManagementViewModel.cs
│   │   │       
│   │   ├───Auth
│   │   │       AdminLoginViewModel.cs
│   │   │       LoginViewModel.cs
│   │   │       RegisterViewModel.cs
│   │   │       
│   │   ├───Booking
│   │   │       BookingViewModel.cs
│   │   │       PaymentViewModel.cs
│   │   │       
│   │   ├───Films
│   │   │       FilmDetailsViewModel.cs
│   │   │       FilmsViewModel.cs
│   │   │       UserFilmsViewModel.cs
│   │   │       
│   │   └───Schedule
│   │           ScheduleViewModel.cs
│   │           ScreeningViewModel.cs
│   │           
│   └───Views
│       │   MainWindow.xaml
│       │   MainWindow.xaml.cs
│       │   
│       ├───Auth
│       │       AdminLoginView.xaml
│       │       AdminLoginView.xaml.cs
│       │       AdminWindow.xaml
│       │       AdminWindow.xaml.cs
│       │       LoginView.xaml
│       │       LoginView.xaml.cs
│       │       LoginWindowView.xaml
│       │       LoginWindowView.xaml.cs
│       │       RegisterWindowView.xaml
│       │       RegisterWindowView.xaml.cs
│       │       UserWindow.xaml
│       │       UserWindow.xaml.cs
│       │       
│       ├───Booking
│       │       BookingView.xaml
│       │       BookingView.xaml.cs
│       │       PaymentView.xaml
│       │       PaymentView.xaml.cs
│       │       
│       ├───Films
│       │       FilmDetailsView.xaml
│       │       FilmDetailsView.xaml.cs
│       │       FilmsView.xaml
│       │       FilmsView.xaml.cs
│       │       
│       └───Schedule
│               ScheduleView.xaml
│               ScheduleView.xaml.cs
│               ScreeningDetailsView.xaml
│               ScreeningDetailsView.xaml.cs
│               
├───Core
│   │   Core.csproj
│   │   
│   ├───bin
│   │   └───Debug
│   │       └───net8.0
│   │               Core.deps.json
│   │               Core.dll
│   │               Core.pdb
│   │               
│   ├───Contracts
│   │       ILogger.cs
│   │       INotificationService.cs
│   │       
│   ├───Enums
│   │       FilmGenre.cs
│   │       UserRole.cs
│   │       
│   ├───Extensions
│   │       DateTimeExtensions.cs
│   │       StringExtensions.cs
│   │       
│   ├───Helpers
│   │       EmailValidator.cs
│   │       PasswordHasher.cs
│   │       
│   ├───Models
│   │       Movie.cs
│   │       
│   └───obj
│       │   Core.csproj.nuget.dgspec.json
│       │   Core.csproj.nuget.g.props
│       │   Core.csproj.nuget.g.targets
│       │   project.assets.json
│       │   project.nuget.cache
│       │   project.packagespec.json
│       │   rider.project.model.nuget.info
│       │   rider.project.restore.info
│       │   
│       └───Debug
│           └───net8.0
│               │   .NETCoreApp,Version=v8.0.AssemblyAttributes.cs
│               │   Core.AssemblyInfo.cs
│               │   Core.AssemblyInfoInputs.cache
│               │   Core.assets.cache
│               │   Core.csproj.AssemblyReference.cache
│               │   Core.csproj.CoreCompileInputs.cache
│               │   Core.csproj.FileListAbsolute.txt
│               │   Core.dll
│               │   Core.GeneratedMSBuildEditorConfig.editorconfig
│               │   Core.GlobalUsings.g.cs
│               │   Core.pdb
│               │   Core.sourcelink.json
│               │   
│               ├───ref
│               │       Core.dll
│               │       
│               └───refint
│                       Core.dll
│                       
├───Data
│   ├───bin
│   │   └───Debug
│   │       └───net8.0
│   └───obj
│       │   Data.csproj.nuget.dgspec.json
│       │   Data.csproj.nuget.g.props
│       │   Data.csproj.nuget.g.targets
│       │   project.assets.json
│       │   project.nuget.cache
│       │   project.packagespec.json
│       │   rider.project.restore.info
│       │   
│       └───Debug
│           └───net8.0
│               │   .NETCoreApp,Version=v8.0.AssemblyAttributes.cs
│               │   Data.AssemblyInfo.cs
│               │   Data.AssemblyInfoInputs.cache
│               │   Data.assets.cache
│               │   Data.csproj.AssemblyReference.cache
│               │   Data.GeneratedMSBuildEditorConfig.editorconfig
│               │   Data.GlobalUsings.g.cs
│               │   
│               ├───ref
│               └───refint
├───Services
│   │   Services.csproj
│   │   
│   ├───bin
│   │   └───Debug
│   │       └───net8.0
│   │               Core.dll
│   │               Core.pdb
│   │               Services.deps.json
│   │               Services.dll
│   │               Services.pdb
│   │               
│   ├───Implementations
│   │       AuthService.cs
│   │       BookingService.cs
│   │       FilmService.cs
│   │       
│   ├───Interfaces
│   │       IAuthDataProvider.cs
│   │       IAuthService.cs
│   │       IBookingService.cs
│   │       IFilmDataProvider.cs
│   │       IFilmService.cs
│   │       IMovieService.cs
│   │       
│   ├───Models
│   │       Booking.cs
│   │       Film.cs
│   │       Screening.cs
│   │       
│   └───obj
│       │   project.assets.json
│       │   project.nuget.cache
│       │   project.packagespec.json
│       │   rider.project.model.nuget.info
│       │   rider.project.restore.info
│       │   Services.csproj.nuget.dgspec.json
│       │   Services.csproj.nuget.g.props
│       │   Services.csproj.nuget.g.targets
│       │   
│       └───Debug
│           └───net8.0
│               │   .NETCoreApp,Version=v8.0.AssemblyAttributes.cs
│               │   Services.AssemblyInfo.cs
│               │   Services.AssemblyInfoInputs.cache
│               │   Services.assets.cache
│               │   Services.csproj.AssemblyReference.cache
│               │   Services.csproj.CoreCompileInputs.cache
│               │   Services.csproj.FileListAbsolute.txt
│               │   Services.csproj.Up2Date
│               │   Services.dll
│               │   Services.GeneratedMSBuildEditorConfig.editorconfig
│               │   Services.GlobalUsings.g.cs
│               │   Services.pdb
│               │   Services.sourcelink.json
│               │   
│               ├───ref
│               │       Services.dll
│               │       
│               └───refint
│                       Services.dll
│                       
└───ViewModels
    ├───bin
    │   └───Debug
    │       └───net8.0
    └───obj
        │   project.assets.json
        │   project.nuget.cache
        │   project.packagespec.json
        │   rider.project.restore.info
        │   ViewModels.csproj.nuget.dgspec.json
        │   ViewModels.csproj.nuget.g.props
        │   ViewModels.csproj.nuget.g.targets
        │   
        └───Debug
            └───net8.0
                │   .NETCoreApp,Version=v8.0.AssemblyAttributes.cs
                │   ViewModels.AssemblyInfo.cs
                │   ViewModels.AssemblyInfoInputs.cache
                │   ViewModels.assets.cache
                │   ViewModels.GeneratedMSBuildEditorConfig.editorconfig
                │   ViewModels.GlobalUsings.g.cs
                │   
                ├───ref
                └───refint
