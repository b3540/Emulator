"EGIoTKit" Project files belong to other solution.
Please add the project into this solution and reference if "EGIoTKit" is unavailable.

EGIoTKit: Gadgeteerのメインボード、センサー等のモジュールのベースとなるクラス群
Emulator、PEACH、SAKURA向けのGadgeteerモジュールは全てここで定義された抽象クラスの派生として実装される

EGIoTKitEmulator: IoT Kitハードウェアのエミュレーター本体
ビルド後のReleaseフォルダーに生成されたライブラリを規定の場所にコピー＆レジストリー登録する

EGIoTKitEmulator.Modules: EGIoTKitEmulatorを利用時のメインボード、センサー等のモジュールの実装
EGIoTKitプロジェクトの中小クラス群のエミュレータ用の実装

EGIoTKitApps: EGIoTKitEmulatorを使うアプリケーションプロジェクトのひな形
このプロジェクトをベースにテンプレートを作成する予定
